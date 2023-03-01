<script>
import HeaderComp from '@/components/Header.vue'
import FooterComp from '@/components/Footer.vue'
import BlockTotal from '@/components/BlockTotal.vue'
import PriceBoard from '@/components/PriceBoardBox.vue'

export default {
    name: 'App',
    components: {
        HeaderComp,
        BlockTotal,
        PriceBoard,
        FooterComp
    }
}
</script>

<template>
    <HeaderComp />
    <div class="main-body">
        <BlockTotal />
        <div class="board">
            <div class="board__container">
                <div class="board__top">
                    <div class="nav nav-tabs nav-tabs-style pl-3" role="tablist" style="border-bottom: none">
                        <a class="nav-item nav-link top active" data-toggle="tab" href="#a" role="tab" aria-controls="a"
                            aria-selected="true">Bảng TT 1</a>
                        <a class="nav-item nav-link top" data-toggle="tab" href="#b" role="tab" aria-controls="b"
                            aria-selected="false">Bảng TT 2</a>
                        <a class="nav-item nav-link top" data-toggle="tab" href="#c" role="tab" aria-controls="c"
                            aria-selected="false">Bảng TT 3</a>
                        <a class="nav-item nav-link top" data-toggle="tab" href="#d" role="tab" aria-controls="d"
                            aria-selected="false"><i class="fas fa-star"></i> Ưa thích</a>
                    </div>

                    <div class="board__search">
                        <div class="board__search-box">
                            <div class="item-search">
                                <input type="text">
                                <span class="text-hook">
                                    Nhập mã TP
                                </span>
                            </div>
                            <button>
                                <i class="fa fa-search-plus"></i>
                            </button>
                        </div>
                        <div class="board__search-sl">
                            <select name="">
                                <option value="">Kỳ hạn còn lại 0-1 Năm</option>
                                <option value="">Kỳ hạn còn lại 0-1 Năm</option>
                                <option value="">Kỳ hạn còn lại 1-3 Năm</option>
                                <option value="">Kỳ hạn còn lại 3-5 Năm</option>
                                <option value="">KHCL trên 5 Năm</option>
                            </select>
                        </div>

                        <div class="nav nav-tabs nav-tabs-style pl-0" role="tablist" style="border-bottom: none;">
                            <a class="nav-item nav-link bottom active" data-toggle="tab" href="#a" role="tab"
                                aria-controls="a" aria-selected="true">VND</a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#b" role="tab" aria-controls="b"
                                aria-selected="false">USD</a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#c" role="tab" aria-controls="c"
                                aria-selected="false"><i class="fas fa-star"></i>
                                Ưa thích</a>
                        </div>
                    </div>
                </div>

                <div class="board__body">
                    <div class="board__nav">
                        <div class="nav nav-tabs nav-tabs-style" role="tablist">
                            <a class="nav-item nav-link bottom active" data-toggle="tab" href="#g" role="tab"
                                aria-controls="g" aria-selected="true">
                                ABCD
                            </a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#h" role="tab" aria-controls="h"
                                aria-selected="false">
                                EFGH
                            </a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#i" role="tab" aria-controls="i"
                                aria-selected="true">
                                IJKL
                            </a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#j" role="tab" aria-controls="j"
                                aria-selected="false">
                                MNOP
                            </a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#k" role="tab" aria-controls="k"
                                aria-selected="true">
                                QRST
                            </a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#l" role="tab" aria-controls="l"
                                aria-selected="false">
                                UVXYZ..
                            </a>
                            <a class="nav-item nav-link bottom" data-toggle="tab" href="#m" role="tab" aria-controls="m"
                                aria-selected="false">
                                <i class="fas fa-star"></i>
                                <span>Ưa thích</span>
                            </a>
                        </div>
                    </div>

                    <PriceBoard />
                </div>
            </div>
        </div>
    </div>
    <FooterComp />
</template>
