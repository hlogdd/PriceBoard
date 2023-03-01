<script>
export default {
    name: 'PriceBoardComp',
}
</script>

<template>
    <div class="board__price">
        <div class="tab-content">
            <div class="tab-pane fade show active" role="tabpanel" aria-labelledby="a-tab">
                <div class="prc-container">
                    <div class="prc-row-head prc-row-head-spec">
                        <div class="prc-col mw-40"><i class="far fa-bookmark"></i></div>
                        <div class="prc-col4 text-center mw-75 mxw-75">
                            Mã TP
                        </div>
                        <div class="prc-col2 text-center th-sort">KHCL</div>
                        <div class="prc-col2 text-center th-sort">Trần</div>
                        <div class="prc-col2 text-center th-sort">Sàn</div>
                        <div class="prc-col2 text-center th-sort">TC
                        </div>
                        <div class="prc-col2 text-center th-sort">G.Mua 3</div>
                        <div class="prc-col2 text-center th-sort">KL 3</div>
                        <div class="prc-col2 text-center th-sort">KL 2</div>
                        <div class="prc-col2 text-center th-sort">Giá 1</div>
                        <div class="prc-col2 text-center th-sort">KL 1
                        </div>
                        <div class="prc-col2 text-center th-sort">Giá khớp</div>
                        <div class="prc-col2 text-center th-sort">+/-</div>
                        <div class="prc-col2 text-center th-sort">%</div>
                        <div class="prc-col2 text-center th-sort">KL khớp</div>
                        <div class="prc-col2 text-center th-sort">Giá 1
                        </div>
                        <div class="prc-col2 text-center th-sort">KL 1</div>
                        <div class="prc-col2 text-center th-sort">Giá 2</div>
                        <div class="prc-col2 text-center th-sort">KL 2</div>
                        <div class="prc-col2 text-center th-sort">Giá 3</div>
                        <div class="prc-col2 text-center th-sort">KL 3
                        </div>
                        <div class="prc-col2 text-center th-sort">Cao nhất</div>
                        <div class="prc-col2 text-center th-sort">Giá TB</div>
                        <div class="prc-col2 text-center th-sort">Thấp nhất</div>
                        <div class="prc-col2 text-center mw-70 th-sort">NN Mua</div>
                        <div class="prc-col2 text-center mw-70 th-sort">NN Bán</div>
                        <div class="prc-col4 text-center mw-90 th-sort">Room</div>
                    </div>
                    <div class="prc-row-body">
                        <div class="prc-row odd">
                            <div class="prc-col text-center mw-40"><span><i class="fas fa-star"></i>;</span>
                            </div>
                            <div class="prc-col4 text-center mw-75 mxw-75" title="ACB - NGAN HANG TMCP A CHAU - HSX"><span
                                    class="clr-up" style="cursor: pointer;">ACB</span></div>
                            <div class="prc-col2 text-right bg-smoke clr-ceil"><span class="">25.9</span></div>
                            <div class="prc-col2 text-right bg-smoke clr-floor"><span class="">22.6</span></div>
                            <div class="prc-col2 text-right bg-smoke clr-ref"><span class="">24.25</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">24.3</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">140,60</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">24.35</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">34,00</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">24.4</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">60</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">24.35</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">0.10</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">0.41%</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">66,80</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">24.45</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">7,90</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">24.5</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">10,00</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">24.55</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">10,00</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">24.75</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">24.37</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-ref"><span class="">24.25</span></div>
                            <div class="prc-col2 text-right mw-70"><span class=""></span></div>
                            <div class="prc-col2 text-right mw-70"><span class=""></span></div>
                            <div class="prc-col4 text-right mw-90"><span class=""></span></div>
                        </div>
                        <div class="prc-row even">
                            <div class="prc-col text-center mw-40"><span><i class="fas fa-star"></i>;</span>
                            </div>
                            <div class="prc-col4 text-center mw-75 mxw-75" title="BCM - TCT DT VA PT CN - CTCP - HSX"><span
                                    class="clr-up" style="cursor: pointer;">BCM</span></div>
                            <div class="prc-col2 text-right bg-smoke clr-ceil"><span class="">89.2</span></div>
                            <div class="prc-col2 text-right bg-smoke clr-floor"><span class="">77.6</span></div>
                            <div class="prc-col2 text-right bg-smoke clr-ref"><span class="">83.4</span>
                            </div>
                            <div class="prc-col2 text-right clr-down"><span class="">82.7</span>
                            </div>
                            <div class="prc-col2 text-right clr-down"><span class="">50</span>
                            </div>
                            <div class="prc-col2 text-right clr-down"><span class="">83</span></div>
                            <div class="prc-col2 text-right clr-down"><span class="">20</span>
                            </div>
                            <div class="prc-col2 text-right clr-down"><span class="">83.2</span>
                            </div>
                            <div class="prc-col2 text-right clr-down"><span class="">90</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">83.5</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">0.10</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">0.12%</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">10</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">83.5</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">50</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">83.8</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">10</span>
                            </div>
                            <div class="prc-col2 text-right clr-up"><span class="">83.9</span></div>
                            <div class="prc-col2 text-right clr-up"><span class="">80</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">84</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-up"><span class="">83.64</span>
                            </div>
                            <div class="prc-col2 text-right bg-smoke clr-down"><span class="">83</span>
                            </div>
                            <div class="prc-col2 text-right mw-70"><span class="">90</span></div>
                            <div class="prc-col2 text-right mw-70"><span class="">40</span></div>
                            <div class="prc-col4 text-right mw-90"><span class="">478,393,86</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="tab-pane fade" role="tabpanel" aria-labelledby="b-tab">
                <div class="block-css">
                    <div class="block-record">
                        <div class="over-flow-x">
                        </div>
                    </div>
                </div>
            </div>

            <div class="tab-pane fade" role="tabpanel" aria-labelledby="c-tab">
                <div class="block-favorite">
                    <div class="over-flow-x">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

