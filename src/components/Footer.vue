<template>
    <footer class="rodape">
        
        <div class="container">
            <div class="item">
                <li class="social-icon"><img src="https://cdn-icons-png.flaticon.com/512/552/552486.png" class="icon-item"><a href="#">Gmail: comercial@stark-marine.com</a></li>
                <li class="social-icon"><img src="https://cdn-icons-png.flaticon.com/512/724/724664.png" class="icon-item"><a href="#">Telephone: +55(21)3197-4415</a></li>
            </div>
            <div class="item">
                <Form />
            </div>
        </div>
    </footer>
</template>
  
<script>

import Form from './Form.vue'
export default {
    name: 'Header',
    components: { Form }
}
</script>
  
<style scoped>
    .link-menu {
        padding: 20px;
    }
    .link {
        list-style: none;
    }
    .link a {
        text-decoration: none;
        font-size: 20px;
        font-weight: 600;
        color: #fff;
    }

    .item {
        display: grid;
        grid-gap: 20px;
    }
    .icon-item {
        width: 90px;
        height: 90px;
    }

    .social-icon {
        list-style: none;
        display: grid;
        grid-auto-flow: column;
        align-items: center;
        gap: 10px;
    }
    .social-icon a {
        text-decoration: none;
        color: #fff;
        font-size: 20px;
        font-weight: 500;
    }
.rodape {
    /* padding: 100px; */
    background-color: #232323;
}
.container {
    display: grid;
    color: #fff;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 600px;
    grid-gap: 10px;
    justify-items: center;
    align-items: center;
}
</style>
  