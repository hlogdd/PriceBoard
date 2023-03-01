<script>
export default {
    name: 'FooterComp',
}
</script>


<template>
    <footer class="footer">
        <div class="footer__time bg-color-bl cl-gray" style="padding: 0 13px">
            <div>
                <div class="date">
                    <div>Ngày GD:<span>12/07/2022</span></div>
                </div>
                <div class="session">
                    <div>Thị trường:<span class="status cl-orange">Đóng cửa</span></div>
                </div>
            </div>

            <div class="times">
                <span>Giờ hệ thống:</span>
                <div class="timer">10:12:45 <span>AM</span></div>
            </div>
        </div>
    </footer>
</template>
