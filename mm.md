<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Markdown Mindmap</title>
    <script src="https://cdn.jsdelivr.net/npm/markmap-view"></script>
</head>
<body>
    <div id="mindmap"></div>
    <script>
        // Create markmap instance
        const { Markmap } = window.markmap;
        
        // Your markdown content
        const markdown = `
# Main Topic
## Subtopic 1
### Point 1
### Point 2
## Subtopic 2
### Point 3
### Point 4
        `;

        // Render the mindmap
        Markmap.create("#mindmap", null, markdown);
    </script>
</body>
</html>
