<template>
    <main>
        <header>
            <h1>REGISTER</h1>

        </header>
        <form @submit.prevent="">
            <label for="">
                <span>Tài Khoản: </span>
                <input type="username" placeholder="Nhập tên tài khoản">
            </label>
            <label for="">
                <span>Mật Khẩu: </span>
                <input type="password"  placeholder="**************">
            </label>
            <label for="">
                <span>Nhập Lại Mật Khẩu: </span>
                <input type="password"  placeholder="**************">
            </label>
            <footer>
                <p>Có tài khoản? <router-link to="/login">Đăng Nhập
                    
                </router-link></p>
            </footer>
            <a to="/" class="btn btn-primary">Đăng Ký</a>
            <!-- <input to="/" class="btn btn-primary" type="submit" value="Đăng Ký"> -->
        </form>
    </main>
</template>

<style>
form{
    border-radius: 1.5rem 1.5rem 0 0;
    background-color: white;
    box-shadow: 0px -4px 12px 4px rgba(0, 0, 0, 0.16);
    color: var(--dark);
    padding: 4rem 1.5rem;
    width: 100%;
}

label{
    display: block;
    margin-bottom: 1.5rem;
}

label span{
    display: block;
    font-size: 1rem;
}

input:not([type="submit"]){
    display: block;
    width: 100%;
    border-radius: 0.5rem;
    padding: 1rem;
    font-size: 1rem;
    font-weight: 300;

}

</style>