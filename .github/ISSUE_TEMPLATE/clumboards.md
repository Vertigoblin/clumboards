---
name: clumboards
about: yuh
title: ''
labels: ''
assignees: ''

---

---
name: "New Image Post"
description: "Submit an image to the board"
title: "[Post] "
body:
  - type: input
    id: title
    attributes:
      label: "Title"
      description: "Enter the title of your post"
      placeholder: "My cool image"

  - type: textarea
    id: description
    attributes:
      label: "Description"
      description: "Write something about your image"
      placeholder: "This is an awesome image!"

  - type: input
    id: image
    attributes:
      label: "Image URL"
      description: "Paste the direct link to an image (e.g., from Imgur)"
      placeholder: "https://i.imgur.com/yourimage.jpg"
