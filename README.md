# Coag Beaker Comment Browser

A client-side web application for browsing and managing coagulation laboratory beaker comments. This tool allows you to search, filter, and draft comments.

## Features

- **Search & Browse**: Search through codes and comments, or browse by category
- **Category Filtering**: Filter results by coagulation test categories (PT/PTT, Lupus Anticoagulant, Protein C/S, etc.)
- **Visual Status Tags**: Color-coded tags showing the status of various analytes (PT, PTT, Protein C, Protein S, Antithrombin, Factors, etc.)
- **Comment Builder**: 
  - Type codes manually and press **F8** to expand them to full comment text
  - Click the **+** button on any code card to add it to the comment builder
  - Build custom comment strings by combining multiple codes

## Usage

### Browsing Codes

1. Use the **search bar** at the top to search for specific terms (e.g., "apixaban", "DRVVT", "Protein S low")
2. Click on **categories** in the left sidebar to filter by test type
3. Use the **sort dropdown** to sort results by relevance, code, or category

### Using the Comment Builder

1. **Manual Entry**: Type codes directly in the Comment Builder textarea (e.g., `N1`, `L1`, `D1`)
2. **Expand Codes**: Position your cursor after a code and press **F8** to expand it to the full comment text
3. **Add from Cards**: Click the **+** button on any code card to add that code to the builder
4. **Build Comments**: Combine multiple codes and expanded text to create custom comment strings

### Example Workflow

```
1. Type "N1" in the comment builder
2. Press F8 → Expands to: "Protein C, protein S, and antithrombin III activity are normal."
3. Click + on code "L1" → Adds "L1" to the builder
4. Press F8 again → Expands "L1" to: "The PTT-LA lupus anticoagulant screen is negative."
```

## Technical Details

- **Pure Client-Side**: No server required - runs entirely in the browser
- **No Dependencies**: Vanilla JavaScript, no external libraries
- **LAMP Compatible**: Can be deployed on any LAMP server without server-side code

## License

This is a client-side application for internal use.

