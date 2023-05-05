<script> 
    import '../app.css';
    import Nav from '$lib/nav.svelte';
    import Fa from 'svelte-fa/src/fa.svelte'
    import { faGithub } from '@fortawesome/free-brands-svg-icons';

</script>

<Nav />
<main>
    <!-- page  content -->
    <slot></slot>
</main>
<footer>
    <p>Copyright 2023 <a href="https://github.com/JeffLi117">JeffLi117 <Fa icon={faGithub} /></a></p>
</footer>