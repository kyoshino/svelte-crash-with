<script>
  import DOMPurify from 'isomorphic-dompurify';
</script>

{DOMPurify.sanitize('<h1>Hello, World!</h1>')}
