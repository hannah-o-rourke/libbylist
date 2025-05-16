# Libby's List

A constituency data explorer built with React and Vite that allows users to view, filter, and download constituency data from a Google Sheets source.

## Features

- 📊 Real-time data loading from Google Sheets
- 🔍 Advanced filtering and search capabilities
- ⬇️ CSV export functionality
- 📱 Responsive design
- 🎯 Constituency-based filtering
- 📋 Sortable data tables

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Lucide Icons

## Environment Variables

Create a `.env` file in the root directory with the following:

```env
VITE_GOOGLE_SHEETS_URL=your_google_sheets_csv_export_url
```

## Development

1. Clone the repository:
```bash
git clone https://github.com/your-username/libbys-list.git
cd libbys-list
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## Building for Production

```bash
npm run build
```

## License

MIT