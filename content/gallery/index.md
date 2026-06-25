---
title: Gallery
date: 2024-10-24
---

**Scenes from life in and around the Trusted Science Center.**

## Southeastern Louisiana University

<div id="campus-gallery" class="masonry-gallery"></div>

## Fieldwork

<div id="fieldwork-gallery" class="masonry-gallery"></div>

## Around the Lab

<div id="lab-gallery" class="masonry-gallery"></div>

## Outdoors and Personal Interests

<div id="outdoors-gallery" class="masonry-gallery"></div>

## Buffalo Bills

<div id="bills-gallery" class="masonry-gallery"></div>

<script>
function addGalleryImages(containerId, folder, prefix, items, altText) {
  const container = document.getElementById(containerId);

  items.forEach(item => {
    const file = `/images/gallery/${folder}/${prefix}${item}.jpg`;

    const link = document.createElement("a");
    link.href = file;
    link.target = "_blank";
    link.rel = "noopener";

    const img = document.createElement("img");
    img.src = file;
    img.alt = altText;
    img.loading = "lazy";

    link.appendChild(img);
    container.appendChild(link);
  });
}

addGalleryImages("campus-gallery", "campus", "campus", [1,2,3,4,5], "Southeastern Louisiana University");

addGalleryImages("fieldwork-gallery", "fieldwork", "fieldwork", [
  1,"1a",2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,
  21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,
  41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,
  61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,
  81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,
  101,102,103,104,105
], "Fieldwork");

addGalleryImages("lab-gallery", "copper", "copper", [
  1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19
], "Copper");

addGalleryImages("lab-gallery", "copper", "buddy", [1,2], "Buddy");

addGalleryImages("outdoors-gallery", "outdoors", "outdoors", [
  1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20
], "Outdoors");

addGalleryImages("bills-gallery", "bills", "bills", [
  1,2,3,4,5,6,7,8,9,10,11,12
], "Buffalo Bills");
</script>