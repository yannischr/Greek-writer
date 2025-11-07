---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
top_imge: https://upload.wikimedia.org/wikipedia/commons/9/94/Wide_brown_land_art-work.JPG

<style>
body {
  background-color: #2c3e50 !important;
  color: #ecf0f1 !important;
  margin: 0;
  padding: 20px;
}

.wrapper {
  background-color: #34495e !important;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  color: #ecf0f1 !important;
}

h1, h2, h3 {
  color: #e74c3c !important;
}

a {
  color: #3498db !important;
}

a:hover {
  color: #e74c3c !important;
}
</style>

<div class="wrapper">
  {{ content }}
</div>
---
