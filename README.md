# boxy-ui

## Purpose
This project aims to simplify the design and usage of basic UI elements while providing flexibility for customization. UI elements include boxes to contain various content types (Box), text display (Text), and embedded content (Embed).

## Main Components

1. **Box Component:**
   - **Description:** The foundational component, Box, serves as a container for UI elements.
   - **Properties:**
     - `role` (e.g., button, video, img, etc.)
     - `style` (CSS-like styling)
     - `content` (other components or content)
   - **Example Usage:**
     ```jsx
     <Box role="button" style={{ backgroundColor: 'blue' }}>Click Me</Box>
     ```

2. **Text Component:**
   - **Description:** Used to display textual content.
   - **Properties:**
     - `text` (the text to be displayed)
     - `style` (styling)
   - **Example Usage:**
     ```jsx
     <Text style={{ fontSize: '16px' }}>Hello, World!</Text>
     ```

3. **Embed Component:**
   - **Description:** Used to display embedded content (e.g., video, map, iframe).
   - **Properties:**
     - `source` (the source of the embedded content)
     - `style` (styling)
   - **Example Usage:**
     ```jsx
     <Embed source="https://www.youtube.com/embed/VIDEO_ID" style={{ width: '100%', height: '300px' }} />
     ```

## Benefits

- **Simplicity and Customization:** Users can customize the basic components (Box, Text, Embed) to create UI elements that suit their needs.
- **Hierarchical Structure:** Users can nest UI elements to create more complex interfaces.
- **Reusability:** Creating and managing these components enhances code reusability.
- **Ease of Maintenance:** Treating UI elements individually simplifies maintenance and development processes.

## Sample Scenario

1. **Creating a Simple Button:**
   Users can create a button using the `<Box>` component with the `role="button"` attribute.
   ```jsx
   <Box role="button" style={{ backgroundColor: 'blue' }}>Click Me</Box>
