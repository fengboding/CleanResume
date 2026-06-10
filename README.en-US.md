# CleanResume

CleanResume is a responsive, privacy-first resume builder crafted with Vanilla JS. Design your resume with a real-time A4 preview, customize templates, and export to PDF—entirely within your browser. No servers, no tracking, no data leaves your device.

---

## Key Features

**Design & Customization**
- **Real-Time A4 Preview**: Instantly see changes on a perfectly scaled, responsive A4 canvas.
- **20 Layout Templates**: Select from 20 distinct combinations of profile alignments, separator positions, icon visibility, and color applications.
- **Typography & Spacing**: Fine-tune font sizes, line heights, margins, and section spacing via intuitive sliders.
- **Watermarks**: Add customizable text watermarks with adjustable opacity, size, and X/Y offsets.
- **Light/Dark Mode**: Toggle shadcn/ui-styled themes for the application interface (the paper preview remains print-ready).

**Editing & Interaction**
- **Drag & Drop**: Reorder sections, entries, and tags effortlessly using mouse or touch gestures.
- **Rich Text**: Format descriptions using Markdown-like syntax for bullet points (`- item`) and bold text (`**text**`).
- **Smart Inputs**: Specialized duration fields and tag inputs (press `Enter` to add tags).
- **Visibility Toggles**: Hide specific sections from the preview without deleting the data.

**Data & Export**
- **One-Click PDF**: Export high-fidelity, A4-sized PDFs automatically named with your name, role, and date. Includes a "Single Page" constraint option.
- **JSON Support**: Import and export your resume data as `.json` files.
- **Drag & Drop Import**: Drop a `.json` file anywhere on the page to import. A validation modal details matched, partial, and ignored fields.
- **Auto-Save**: All data, UI states, and settings are saved locally and persist across sessions.

---

## Locale Support (`en-US`)

CleanResume automatically detects your system language and adapts the UI. If English is selected:

- **Default Sections**: Education, Experience, Projects, Awards, Certifications, Skills, Languages.
- **Sample Data**: Loads an English resume featuring Western names and institutions.

---

## Getting Started

### 1. Editing
- **Open Editor**: Click the "Pen-line" floating button on the right to open the Editor Panel.
- **Add Content**: Use the "Add" footer button to create sections. Click the "+" icon within a section to add entries.
- **Format Text**: Type `- ` for bullets and `**text**` for bold in description fields.

### 2. Styling
- **Open Settings**: Click the "Settings" floating button to open the Settings Panel.
- **Choose Template**: Select a mini-preview card to set the base layout.
- **Apply Colors**: Pick an accent color to theme names, headers, icons, or tags based on the template.
- **Adjust Layout**: Use sliders for typography, spacing, padding, and watermark configuration.

### 3. Data Management
- **Import**: Click "Import" or drag a `.json` file onto the page. Review the validation table to ensure data integrity.
- **Export JSON**: Click "Export" to download a portable `.json` backup of your data.
- **Save PDF**: Click the "Download" button to generate a PDF. If "Single Page" is enabled, content scales to fit one page.

---

## Tips

- **Collapsible UI**: Click the chevron icon on sections or entries to collapse them and keep the editor tidy.
- **Smart Key Fields**: New entries display a random ID that automatically updates to your University or Company name once typed.
- **Import Validation**: Click any row in the import validation modal to expand and see exactly which fields matched.
- **Empty State**: When the resume is empty, the preview cycles through helpful setup tips.

---

*Built with Vanilla JS, Tailwind CSS, and Lucide Icons.*
