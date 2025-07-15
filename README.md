# Data Schema Modeler

A powerful web application for visualizing and editing data schemas with drag-and-drop functionality.

## Features
- Interactive schema visualization
- Drag and drop table positioning
- Real-time relationship management
- JSON import/export
- Auto layout and search functionality
- Minimap for navigation

## Usage
1. Open `index.html` in a web browser
2. Paste your JSON schema in the sidebar
3. Click "Load Schema" to visualize
4. Drag tables and create relationships
5. Export your modified schema

## Live Demo
[Add your GitHub Pages URL here]

## JSON Format
```json
{
  "relationships": [
    {
      "from_table": "table1.csv",
      "from_column": "column1",
      "to_table": "table2.csv", 
      "to_column": "column2",
      "confidence": 1.0
    }
  ],
  "created_at": "2025-07-15T11:26:57.984604",
  "version": "initial"
}
