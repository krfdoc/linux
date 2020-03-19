layout: page
title: "symlink"
permalink: https://krfdoc.github.io/linux/symlink

<! Template for Copy/Paste Line -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>target-div</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
    <!-- 1. Define some markup -->
    <div>This line is copied, it will help you with your documentation project</div>
    <button class="btn" data-clipboard-action="copy" data-clipboard-target="div">Copy</button>

    <!-- 2. Include library -->
    <script src="../dist/clipboard.min.js"></script>

    <!-- 3. Instantiate clipboard -->
    <script>
    var clipboard = new ClipboardJS('.btn');

    clipboard.on('success', function(e) {
        console.log(e);
    });

    clipboard.on('error', function(e) {
        console.log(e);
    });
    </script>
</body>
</html>

