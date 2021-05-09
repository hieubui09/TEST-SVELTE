<script>
    let changeLanguage = false;
    let changeMenu = false;
</script>

<main>
    <div class="header">
        <div class="logo">
            <div class="logo__img">
                <img src="images/logo_bitking.png" alt="" />
            </div>
            <div
                class="eng"
                id="language"
                on:click={() => {
                    changeLanguage = !changeLanguage;
                }}
            >
                <i class="fas fa-globe" />
                <p>ENG</p>
                <img class="eng__vector" src="images/Vector.png" alt="" />
                <div class="VNM" class:VNM--active={changeLanguage}>
                    <a href="" id="vn">VN</a>
                </div>
            </div>
        </div>
        <div class="menu__all">
            <div class="menu__mobi"  on:click={() => {
                changeMenu = !changeMenu;
            }}>
                <div>
                    <img
                        class="cate__vector"
                        src="images/category.png"
                        alt=""
                    />
                </div>
                <div  class="nav__mobi" class:nav__mobi--active={changeMenu}>
                    <ul>
                        <li><a href="">Giới thiệu</a></li>
                        <li><a href="">Lợi ích</a></li>
                        <li><a href="">Buy BKT</a></li>
                        <li><a href="">Hướng dẫn</a></li>
                        <li><a href="">Liện hệ</a></li>
                    </ul>
                 </div>
            </div>
            <div class="menu__desktop">
                <ul>
                    <li><a href="">Giới thiệu</a></li>
                    <li><a href="">Lợi ích</a></li>
                    <li><a href="">Buy BKT</a></li>
                    <li><a href="">Hướng dẫn</a></li>
                    <li><a href="">Liện hệ</a></li>
                </ul>
            </div>
        </div>
        <div class="join">
            <div class="join__Now">
                <p>join Now &#10141;</p>
            </div>
        </div>
    </div>
</main>

<style lang="scss">
    @import "../scss/header.scss";
</style>
