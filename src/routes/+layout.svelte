<nav>
    <div class="nav-container">
        <a href="/" class= "nav/logo" title="Back to Homepage">Руслан Догадаев</a>
        <div class="nav-links">
            <a href="/about" class="link">Обо мне</a>
            <a href="/blog" class="link">Блог</a>
            <a href="/project" class="project">Портфолио</a>
            <a href="/contact" class="contact">Контакты</a>
        </div>
    </div>
</nav>
<div class="container">
   <slot></slot>
</div>
<style>
    .container{
        max-width: 1400px;
        margin: 50px auto;
    }
</style>