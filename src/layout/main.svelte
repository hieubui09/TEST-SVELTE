<script>
    import { Swipe, SwipeItem } from "svelte-swipe";
    const swipeConfig = {
        autoplay: false,
        delay: 2000,
        showIndicators: false,
        transitionDuration: 1000,
        defaultIndex: 0,
    };
    let SwipeComp;
    function nextSlide() {
        SwipeComp.nextItem();
    }
    function prevSlide() {
        SwipeComp.prevItem();
    }
    let screenWidth= window.innerWidth;
</script>

<main>
    <section>
        <div class="Lighthouse">        
            <div class="Lighthouse__text">
                <h1>Nền tảng tài chính thông minh hàng đầu trên thế giới</h1>
                <p>
                    Tham gia Bitkingreturns của chúng tôi để xây dựng <br /> một
                    nền kinh tế phi tập trung hoàn toàn minh bạch
                </p>
                <div>
                    <button>Tham gia</button>
                    <u>Tìm hiểu thêm</u>
                    <!-- <p> &#10141;</p> -->
                </div>
            </div>
                     
            <div class="Lighthouse__img">
                <img class="img_01" src="images/Vector99.png" alt="">
                <img  class="img_02" src="images/Vector98.png" alt="">
                <img class="img_03" src="images/Group B.png" alt="" />
            </div>
        </div>
        <div class="wrapper">
            <div class="trademark">
                <div><img src="images/bcio.png" alt="" /></div>
                <div><img src="images/Group.png" alt="" /></div>
                <div><img src="images/Groupgalaxy.png" alt="" /></div>
                <div><img src="images/Vector01.png" alt="" /></div>
                <div><img src="images/Techkon_logo.png" alt="" /></div>
            </div>
            <div class="title">
                <h2>Khoản đầu tư <br /> tốt nhất cho bạn</h2>
            </div>
            <div class="content">
                <div>
                    <img src="images/docquyen.png" alt="" />
                    <h3>Độc quyền</h3>
                    <p>
                        Chúng tôi đã tạo ra công thức cho một nền kinh tế tự
                        động thông minh. Nơi mà mỗi cá nhân đều có thể tham gia
                        dễ dàng và tạo ra nhiều lợi nhuận
                    </p>
                </div>
                <div>
                    <img src="images/dongian.png" alt="" />
                    <h3>Đơn giản</h3>
                    <p>
                        Hệ thống trải nghiệm người dùng đơn giản, không yêu cầu
                        KYC, không giới hạn rút và nạp tiền
                    </p>
                </div>
                <div>
                    <img src="images/minhbach.png" alt="" />
                    <h3>Minh bạch</h3>
                    <p>
                        Bạn có thể biết được mọi thứ ở đây. Chúng tôi là một
                        trong những nền tảng đáng tin cậy nhất trên thế giới
                    </p>
                </div>
            </div>
            <div class="content__dautu">
                <div class="dautu__text">
                    <h3>Mua BTR</h3>
                    <h2>Mã thông báo trên TRON tốt nhất</h2>
                    <p>
                        Chúng tôi sử dụng TRON như một công nghệ mới và xây dựng
                        BTR trên nền tảng hợp đồng thông minh. TRON giúp cung
                        cấp đầy đủ công cụ để tạo ra những mã thông báo hàng đầu
                        trên thế giới, trong đó bao gồm BTR – hứa hẹn sẽ phát
                        triển mạnh mẽ trong năm 2021
                    </p>
                    <button>Tham Gia &#10141;</button>
                </div>
            </div>
            <div class="title">
                <h2>Lợi ích của <br /> Bitkingreturns</h2>
            </div>
            <div class="grid-container">
                <div class="item1__grid">
                    <div class="item1__text">
                        <img src="images/01.png" alt="" />
                        <h3>
                            Chia sẻ giúp bạn tạo ra một khoản lợi nhuận lớn mỗi
                            ngày
                        </h3>
                        <p>
                            Bạn sẽ nhận được nhiều hoa hồng mỗi ngày thông qua
                            số lượng vé mua mà bạn đã giới thiệu. Nền tảng
                            Bitkingreturns hoàn toàn tự động rút tiền và nạp
                            tiền.
                        </p>
                        <div>
                            <u class="read">
                                Read more
                            </u>
                            <p> &#10141;</p>
                        </div>
                        
                    </div>
                </div>
                <div class="item2__grid">
                    <div class="item2__text">
                        <img src="images/02.png" alt="" />
                        <h3>Hệ thống bảo vệ tài sản nhiều tầng</h3>
                        <p>
                            Chúng tôi đã xây dựng hệ thống bảo vệ chắc chắn và
                            chi tiết để ngăn chặn những tin tặc, những kẻ lừa
                            đảo tấn công và lấy cắp tài sản của bạn
                        </p>
                        <div>
                            <u class="read">
                                Read more
                            </u>
                            <p> &#10141;</p>
                        </div>
                    </div>
                </div>
                <div class="item3__grid">
                    <div class="item3__text">
                         <div>
                           <img src="images/Ellipse 2.png" alt="">
                       </div>
                        <img src="images/03.png" alt="" />
                        <h3>Kiếm tiền trở nên dễ dàng với Bitkingreturns</h3>
                        <p>
                            Bạn đang tìm kiếm một nền tảng tài chính an toàn,
                            đáng tin cậy và tạo ra nhiều lợi nhuận trong tương
                            lai? Vậy thì Bitkingreturns - nền tảng được xây dựng
                            trên công trình nghiên cứu của hơn 30 giáo sư kinh
                            tế hàng đầu trên thế giới - chính là giải pháp hoàn
                            hảo cho bạn.
                        </p>
                        <div>
                            <u class="read">
                                Read more
                            </u>
                            <p> &#10141;</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="space">
            <h3 />
        </div>
        <div class="content_kiemtien">
            <div class="slider">
                <Swipe bind:this={SwipeComp} {...swipeConfig}>
                    {#if screenWidth>568 }  
                    <SwipeItem>
                        <div class="slider__row">
                            <div class="slide__item1">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Mua vé</h3>
                                    <p>Mua vé của bạn để bắt đầu đầu tư</p>
                                </div>
                            </div>
                            <div class="slide__item2">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Theo dõi lợi nhuận</h3>
                                    <p>Theo dõi lợi nhuận của từng vé</p>
                                </div>
                            </div>
                            <div class="slide__item3">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Chia sẻ</h3>
                                    <p>
                                        Chia sẻ để xây dựng khoản lợi nhuận lớn
                                        mỗi ngày
                                    </p>
                                </div>
                            </div>
                        </div>
                    </SwipeItem>
                    <SwipeItem>
                        <div class="slider__row">
                            <div class="slide__item1">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Mua vé</h3>
                                    <p>Mua vé của bạn để bắt đầu đầu tư</p>
                                </div>
                            </div>
                            <div class="slide__item2">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Theo dõi lợi nhuận</h3>
                                    <p>Theo dõi lợi nhuận của từng vé</p>
                                </div>
                            </div>
                            <div class="slide__item3">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Chia sẻ</h3>
                                    <p>
                                        Chia sẻ để xây dựng khoản lợi nhuận lớn
                                        mỗi ngày
                                    </p>
                                </div>
                            </div>
                        </div>
                    </SwipeItem>
                    <SwipeItem>
                        <div class="slider__row">
                            <div class="slide__item1">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Mua vé</h3>
                                    <p>Mua vé của bạn để bắt đầu đầu tư</p>
                                </div>
                            </div>
                            <div class="slide__item2">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Theo dõi lợi nhuận</h3>
                                    <p>Theo dõi lợi nhuận của từng vé</p>
                                </div>
                            </div>
                            <div class="slide__item3">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Chia sẻ</h3>
                                    <p>
                                        Chia sẻ để xây dựng khoản lợi nhuận lớn
                                        mỗi ngày
                                    </p>
                                </div>
                            </div>
                        </div>
                    </SwipeItem>
                    {:else}
                    <SwipeItem>
                        <div class="slider__row">
                            <div class="slide__item1">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Mua vé</h3>
                                    <p>Mua vé của bạn để bắt đầu đầu tư</p>
                                </div>
                            </div>
                            
                        </div>
                    </SwipeItem>
                    <SwipeItem>
                        <div class="slider__row">
                            <div class="slide__item1">
                                <div class="slide__text">
                                    <img src="images/star 1.png" alt="" />
                                    <h3>Mua vé</h3>
                                    <p>Mua vé của bạn để bắt đầu đầu tư</p>
                                </div>
                            </div>                       
                        </div>
                    </SwipeItem>
                    {/if}
                </Swipe>

                <div class="button__btn">
                    <div class="prev" on:click={prevSlide}>
                        <img src="images/one1.png" alt="" />
                    </div>
                    <div class="next" on:click={nextSlide}>
                        <img src="images/one2.png" alt="" />
                    </div>
                </div>
            </div>
            <div class="kiemtien_title">
                <p>Làm sao để bắt đầu?</p>
                <h3>Bắt đầu kiếm tiền Với những bước đơn giản</h3>
                <p class="p">
                    Bắt đầu với những bước đơn giản: Đầu tư ngay trong tầm bay
                    bạn từ những bước click chuột đơn giản
                </p>
            </div>
        </div>
        <div class="wrapper">
            <div class="content_laptop">
                <div class="laptop_title">
                    <h2>Responsible</h2>
                    <h3>Tương thích với tất cả các loại màn hình</h3>
                    <p>
                        Trang web của chúng tôi được nâng cấp và có thể tương
                        thích với các loại màn hình khác nhau như Iphone, Ipad,…
                        Không gây khó chịu và nhiều hạn chế khi sử dụng so với
                        các nền tảng khác.
                    </p>
                </div>
            </div>
            <div class="title">
                <h3>
                    Mạng lưới của chúng tôi có mặt trên <br /> tất cả các quốc gia
                    trên thế giới
                </h3>
            </div>
        </div>
        <div class="content_world">
            <div class="flex">
                <div><img src="images/Vector_user.png" alt="" /></div>
                <div class="flex_text">
                    <h1>3423</h1>
                    <p>Người dùng</p>
                </div>
            </div>
            <div class="flex">
                <div><img src="images/Vector_011.png" alt="" /></div>
                <div class="flex_text">
                    <h1>45463</h1>
                    <p>Vé trung bình mỗi ngày</p>
                </div>
            </div>
            <div class="flex">
                <div><img src="images/Vector_002.png" alt="" /></div>
                <div class="flex_text">
                    <h1>80%</h1>
                    <p>Người dùng chiến thắng</p>
                </div>
            </div>
        </div>
        <div class="content_thamgia">
            <h1>Kiếm tiền thật dễ dàng trên nền tảng Bitkingreturns</h1>
            <button class="now">Tham Gia ngay &#10140;</button>
            <button class="add">Tìm hiểu thêm &#10140;</button>
        </div>
    </section>
</main>

<style lang="scss">
    @import "../scss/main.scss";
</style>
