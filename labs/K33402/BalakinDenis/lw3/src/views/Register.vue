<template>
    <main class="vw-100 d-flex align-items-center justify-content-center">
        <section class="d-flex flex-column mt-5">
            <h2 class="mt-5">Register</h2>
            <form>
                <div class="mb-3">
                    <label for="exampleInputNickname" class="form-label">Nickname</label>
                    <input type="text" placeholder="Input nickname" class="form-control" id="exampleInputNickname" aria-describedby="emailHelp">
                    <div  class="form-text ">Сome up with a nickname.</div>
                </div>
                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Email address</label>
                    <input type="email" placeholder="Input email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                </div>
                <div class="mb-3">
                    <label for="exampleInputPassword1" class="form-label">Confirm password</label>
                    <input type="password" placeholder="Confirm password" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="mb-3">
                    <label for="exampleInputPassword2" class="form-label">Password</label>
                    <input type="password" placeholder="Input password" class="form-control" id="exampleInputPassword2">
                </div>
                <div class="mb-3 form-check">
                    <input type="checkbox" class="form-check-input" id="exampleCheck1">
                    <label class="form-check-label" for="exampleCheck1">Check me out</label>
                </div>
                <button type="submit" class="btn text-white bg-orange">Submit</button>
            </form>
        </section>
    </main>
</template>

<script>
    export default {
        name: "Register"
    }
</script>

<style scoped>
    .form-text {
        color: var(--body-color);
    }
    .bg-orange {
        background: var(--btn-color);
        padding-left: 20px;
        padding-right: 20px;
    }
</style>
