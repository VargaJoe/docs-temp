---
title: Preview
metaTitle: "sensenet API - Preview"
metaDescription: "Preview"
---

Following actions were designed to support the client-side preview component (document viewer) that displays document preview images.

# Get page count

Returns the number of pages in a document. If there is no information about page count on the content, it starts a preview generation task to determine the page count.

<tab category="preview" article="preview" example="getPageCount" />

# Check previews

Returns the number of currently existing preview images. If necessary, it can make sure that all preview images are generated and available for a document.

<tab category="preview" article="preview" example="checkPreviews" />

# Regenerate previews

It clears all existing preview images for a document and starts a task for generating new ones. This can be useful in case the preview status of a document has been set to ‘error’ before for some reason and you need to force the system to re-generate preview images.

<tab category="preview" article="preview" example="regeneratePreviews" />

# Commenting preview images

!TODO!
