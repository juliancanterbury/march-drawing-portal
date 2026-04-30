MARCH Drawing Portal — clickable proof of concept

Open index.html in a browser.

What works in this static mock-up:
- Discipline tabs: Architectural, Structural, Civil, Mechanical, Electrical, Other
- Drawing list with current/superseded states
- Click a drawing row to preview it
- Preview pane with fake PDF toolbar
- Download button logs a fake download in the activity log
- Show/hide superseded drawings
- Select drawings and create a fake transmittal
- Register/export buttons show placeholder behaviour

This version uses local SVG drawing placeholders instead of real PDFs.
The next stage would replace the local drawing data with either:
1. a Google Sheet drawing register; and
2. Google Drive PDF preview URLs of the form:
   https://drive.google.com/file/d/FILE_ID/preview

For GitHub Pages:
1. Create a new repository.
2. Upload the whole folder contents.
3. Go to Settings > Pages.
4. Source: Deploy from branch.
5. Branch: main / root.
6. Open the GitHub Pages URL.
