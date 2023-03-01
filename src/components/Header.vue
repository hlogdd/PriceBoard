<script>
export default {
    name: 'HeaderComp',
}
</script>


<template>
    <header class="header">
        <div class="header__wrap">
            <div class="header__bottom header__bottom-padding">
                <div class="logo">
                    <a href="#">
                        <!-- <img src="./image/img/logo_hnx.png" alt="logo"> -->
                    </a>
                </div>

                <div class="navigation">
                    <ul class="navigation-box navigation-color navigation-focus-no">
                        <li>
                            <a href="#">Bảng Tổng hợp GD Khớp lệnh</a>
                        </li>
                        <li class="active">
                            <a class="navigation-item" href="#">Bảng chào giá GD Outright</a>
                        </li>
                        <li>
                            <a href="#">Bảng Tổng hợp GD Outright</a>
                        </li>
                        <li>
                            <a href="#">Bảng in Repo</a>
                        </li>
                        <li>
                            <a href="#">Bảng Tổng hợp GD Repo</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>
