<script> 
    import '../app.css';
    import Fa from 'svelte-fa/src/fa.svelte'
    import { faGithub } from '@fortawesome/free-brands-svg-icons';
</script>

<h1>CreationsByNight</h1>
<p>Anonymously artistic.</p>
<p>Creatively crafty.</p>
<p>I hope you like what you see.</p>
<nav>
    <ul class="ulHome" >
        <li><a href="/">Home</a></li>
        <li><a href="/portfolio">Portfolio</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>

<footer>
    <p>Copyright 2023 <a href="https://github.com/JeffLi117">JeffLi117 <Fa icon={faGithub} /></a></p>
</footer>
<style>
    nav, ul.ulHome {
        text-align: left;
        display: flex;
        justify-content: flex-start;
        align-items: center;
        padding: 0;
    }
    a:link, a:visited {
        color: white;
        text-decoration: none;
    }
    a:hover {
        color: rgb(190, 100, 255);
        text-decoration: none;
    }
    a:active {
        color: orangered;
        text-decoration: none;
    }
    footer {
        padding: 5px;
        font-size: 0.9rem;
        opacity: 0.7;
    }
</style>