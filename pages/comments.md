---
layout: page
title: "Comments"
permalink: /comments/
bluesky_post_uri: "https://bsky.app/profile/elouan.xyz/post/3lbta5sfvhs2w"
weight: 7
---

<link rel="stylesheet" href="https://unpkg.com/bluesky-comments@0.3.0/dist/bluesky-comments.css">

<script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
<script src="https://unpkg.com/bluesky-comments@0.3.0/dist/bluesky-comments.umd.js"></script>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const uri = 'https://bsky.app/profile/elouan.xyz/post/3lbta5sfvhs2w'
    if (uri) {
      initBlueskyComments('bluesky-comments', uri);
    } 
  });
</script>