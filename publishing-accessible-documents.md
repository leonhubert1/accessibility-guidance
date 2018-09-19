# Publishing accessible documents

Documents published on GOV.UK or other [public sector websites must meet accessibility standards] (https://www.gov.uk/guidance/accessibility-requirements-for-public-sector-websites-and-apps). This is so they can be used by as many people as possible, including those with disabilities.

If your document does not meet the standards, you could be breaking the law.

## What to do as a document author

Follow these steps when you write a document. If you have questions, contact your website publishing team.

### 1. Think about format

Wherever possible, publish in HTML. It’s the best way to reach as many people as possible.

Documents like PDFs make your content [harder to find, use and maintain](https://gds.blog.gov.uk/2018/07/16/why-gov-uk-content-should-be-published-in-html-and-not-pdf/). And it can be difficult for users to customise them for ease of reading, and often they do not work very well with assistive technologies like screen readers.

Contact your website team to find out more about publishing in HTML.

If you do need to publish a document, it should be in addition to an HTML version.

### 2. Keep the language simple

Write in language that’s as simple as possible.

Simple language makes your document accessible to people with cognitive impairments and learning disabilities.

And research shows that everyone prefers simple language, including specialist audiences. Because it allows them to understand information as quickly as possible.

Where you need to use technical terms, abbreviations or acronyms, explain what they mean the first time you use them.

### 3. Keep the document simple

Keep sentences and paragraphs short. 

Use a sans serif font like Arial or Helvetica. Use a minimum size of 12 points.

Use sentence case. Avoid all caps text and italics.

Make sure the text is left aligned, not justified.

Avoid underlining, except for links.

Documents with single, continuous columns of text are easier to make accessible than documents with a more complex layout.

Only use tables for data. Keep tables simple: avoid splitting or merging cells.

Do not use colour alone to get across meaning.

If you’re using images, think about how you’ll make the content accessible to people with a visual impairment. Two options are:

- make the same point in the text of the document (so people with visual impairments get the information they need - the image is there as an extra for people who are able to see it)
- give the person converting or uploading the document for you [alt text (‘alternative text’)](https://webaim.org/techniques/alttext/) for the image

Avoid footnotes where possible. Provide explanations inline instead.

### 3. Give the document a structure

Break up your document to make it more readable. Use bullet points, numbered steps and subheadings.

Do not use bold to mark up subheadings. Use styles to create a hierarchy of headings: ‘heading 1’, ‘heading 2’ and so on. Ask your website publishing team if you’re not sure how to do this.

### 4. Forms, complex documents and other office formats

If you’re creating another type of office document (for example a spreadsheet or presentation), there’s guidance on how to make it accessible on the [Accessible Digital Office Document Project](https://adod.idrc.ocadu.ca/) website.

If you’re creating a form or other document with complex formatting, you can follow the instructions on [making accessible PDFs in InDesign](https://www.adobe.com/content/dam/acom/en/products/indesign/pdfs/creating-accessible-pdf-documentw-with-adobe-indesign-cs6-v3.pdf) (PDF, 1.4MB).

## Creating a PDF from a scanned document

If you’re creating a PDF by scanning a paper document, use [Optical Character Recognition (OCR)](https://acrobat.adobe.com/uk/en/acrobat/how-to/ocr-software-convert-pdf-to-text.html) to make the PDF accessible to screen reader users.

## Converting or uploading a document

Wherever possible, create content in HTML formats. If you need to publish a document in another format, it should be in addition to an HTML version.

If you do need to upload a non-HTML document, follow this guidance:

- [how to convert a Word document to accessible PDF format](https://webaim.org/techniques/acrobat/converting)
- [how to format a Word document so it’s accessible](https://support.office.com/en-us/article/Make-your-Word-documents-accessible-d9bf3683-87ac-47ea-b91a-78dcacb3c66d)

## Check a document for accessibility

Once you’ve followed the steps to make your document accessible, check it before publishing.

You can pick up many accessibility issues by running some automated tests on your document.

^To check your document fully meets accessibility standards, you’ll also need to do manual testing. Use the [accessibility checklist created by 18F](https://accessibility.18f.gov/checklist/) (the US government’s digital agency) to help you with your manual testing.

### PDFs

To check your PDF is accessible you can use Adobe Reader or Adobe Acrobat Pro. You should also test your PDF is accessible using a screen reader.

#### Adobe Reader

You can use Adobe Reader to find out if your PDF document is correctly tagged and structured. People using screen readers need these to be able to access your document.

Go to ‘Edit’ then ‘Accessibility’ and select ‘Quick check’. To fix any issues, you’ll need to either fix the original document in Word or use Adobe Acrobat Pro.

#### Adobe Acrobat Pro

Follow Adobe’s instructions on [using Acrobat Pro to check if your PDF is accessible](https://helpx.adobe.com/acrobat/using/create-verify-pdf-accessibility.html).

The PDF should pass the full check for WCAG Level AA without any warnings.

#### Quick screen reader check

Ask a screen reader user to read through the PDF. If no-one is available to do this, use one of the following options instead.

#### If you’re using Windows

[Non Visual Desktop Access (NVDA)](http://www.nvda-project.org/) is a free open source screen reader for Windows. It can be installed to the desktop or run from a portable USB drive.

With NVDA running, open the PDF and use the following commands to check the PDF:

- from the top of the PDF (with the numlock off), use Numpad 0 + Numpad 2 to read the PDF from top to bottom and check the reading order
- use the tab key to move through the PDF and check the tab order
- use the h key to move through the PDF and check the heading structure
- use the g key to move through the PDF and check for text descriptions

These commands will also work with the Jaws screen reader from Freedom Scientific.

#### If you’re using a Mac

All Apple Macs have VoiceOver built in. Turn VoiceOver on (or off again) using Command + f5. With VoiceOver running open the PDF and use the following commands to check the PDF:

- from the top of the PDF use a double finger down swipe, or ‘Control + Option + a’ to read the PDF from top to bottom and check the reading order
- use the tab key (repeatedly) to move through the PDF and check the tab order.

VoiceOver does not provide shortcut keys for navigating by headings or graphics.

### Microsoft Office

Use the [accessibility checker](https://support.office.com/en-us/article/use-the-accessibility-checker-to-find-accessibility-issues-a16f6de0-2f39-4a2b-8bd8-5ad801426c7f) to see if Word, Excel and other Microsoft Office documents are accessible.
