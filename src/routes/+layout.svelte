<script>
    import Nav from "../components/Nav.svelte";
    import Logo from "../components/Logo.svelte";
</script>
<Nav></Nav>
<Logo size="5em" color="#000" />
<p>asad</p>
<!-- <nav>
    <ul>
      <li><a href="/">🏠</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/cv">CV</a></li>
      <li><a href="/about">About</a></li>
    </ul>
  </nav>
  
  <slot />
  
  <style>
    nav {
      display: flex;
      justify-content: space-around;
      padding: 1rem;
      background-color: #f8f9fa;
    }
  
    ul {
      list-style: none;
      display: flex;
      gap: 1rem;
      padding: 0;
      margin: 0;
    }
  
    li {
      margin: 0;
    }
  
    a {
      text-decoration: none;
      color: #0070f3;
      font-weight: bold;
    }
  
    a:hover {
      text-decoration: underline;
    }
  </style> -->


<slot></slot>