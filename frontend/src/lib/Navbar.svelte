<script>
    // Import necessary functions from SvelteKit for navigation
    import { navigate } from "svelte-routing";
  </script>
  
  <nav class="navbar">
    <ul>
        <li><a href="/" sveltekit:prefetch>Home</a></li>
        <li><a href="/page1" sveltekit:prefetch>Page 1</a></li>
        <li><a href="/page2" sveltekit:prefetch>Page 2</a></li>
    </ul>
  </nav>
  
  <style>
    .navbar {
      display: flex;
      justify-content: space-around;
      background-color: #f0f0f0;
      padding: 10px 0;
    }
    a {
      color: #333;
      text-decoration: none;
      padding: 10px;
    }
  </style>
  