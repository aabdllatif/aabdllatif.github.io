<!-- ---
layout: default
title: Redirect Handler
permalink: /papers/
---

<script>
  const path = window.location.pathname; 
  const fileName = path.split('/').pop();

  if (fileName) {
    // Redirect to the new location in /assets/pdf/
    window.location.href = `/assets/pdf/${fileName}`;
  } else {
    document.body.innerHTML = '<h1>Error: No file specified for redirection.</h1>';
  }
</script> -->