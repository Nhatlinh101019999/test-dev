<template>
  <div class=" flex flex-wrap pt-[30px]">
    <div>
      <div class="w-full bg-[#f4f4f4] rounded-3xl">
        <ul class="flex mb-0 list-none flex-wrap flex-row bg-white">
          <li class="-mb-px  last:mr-0 flex-auto text-center" :class="{' bg-white ': openTab !== 1, 'text-black bg-[#f4f4f4]': openTab === 1}" @click="toggleTabs(1)">
            <div class="box-shadow bg-white m-8 rounded-lg">
              <div class="py-6">
                <img class="m-auto" src="images/icontab.png" alt="">
                <a class="font-bold text-xl px-5 py-3 rounded block leading-normal"> Pencils
                </a>
              </div>
            </div>
          </li>
          <li class="-mb-px  last:mr-0 flex-auto text-center" :class="{' bg-white ': openTab !== 2, 'text-black bg-[#f4f4f4]': openTab === 2}" @click="toggleTabs(2)">
            <div class="box-shadow bg-white m-8 rounded-lg">
              <div class="py-6">
                <img class="m-auto" src="images/icontab.png" alt="">
                <a class="font-bold text-xl px-5 py-3 rounded block leading-normal"> Markers
                </a>
              </div>
            </div>
          </li>
          <li class="-mb-px  last:mr-0 flex-auto text-center" :class="{' bg-white ': openTab !== 3, 'text-black bg-[#f4f4f4]': openTab === 3}" @click="toggleTabs(3)">
            <div class="box-shadow bg-white m-8 rounded-lg">
              <div class="py-6">
                <img class="m-auto" src="images/icontab.png" alt="">
                <a class="font-bold text-xl px-5 py-3 rounded block leading-normal"> Drawing Colors
                </a>
              </div>
            </div>
          </li>
          <li class="-mb-px  last:mr-0 flex-auto text-center" :class="{' bg-white ': openTab !== 4, 'text-black bg-[#f4f4f4]': openTab === 4}" @click="toggleTabs(4)">
            <div class="box-shadow bg-white m-8 rounded-lg">
              <div class="py-6">
                <img class="m-auto" src="images/icontab.png" alt="">
                <a class="font-bold text-xl px-5 py-3 rounded block leading-normal"> Notebooks
                </a>
              </div>
            </div>
          </li>
        </ul>
        <div class="relative flex flex-col min-w-0 break-words w-full mb-6  rounded">
          <div class="px-4 py-5 flex-auto">
            <div class="tab-content tab-space">
              <div :class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                <div class="grid grid-cols-3 gap-4">
                  <div>
                    <p class="text-xl font-semibold p-8">
                      Graphite Artist Quality Fine Art Drawing and Sketching Pencils Replaceable Nib Pencils.
                    </p>
                    <ul class="list-block px-8">
                      <li>MECHANICAL PENCILS</li>
                      <li>ARCHITECT'S CHOICE</li>
                      <li>EXECUTIVE PENCILS</li>
                      <li>ENGRAVABLE PENCILS</li>
                    </ul>
                    <button class="py-3.5 px-6 bg-[#F4B840] rounded-md text-sm font-bold text-white  mt-9 ml-8">
                      SHOP ALL
                    </button>
                  </div>
                  <div class="col-span-2">
                    <div class="grid grid-cols-4 gap-8 bg-white rounded-2xl mb-4">
                      <div class="custom-sale flex justify-center">
                        <h2 class="text-[#F4B840]">
                          25% off
                        </h2>
                      </div>
                      <div class="custom col-span-3 ">
                        <p>Offer Applicable on All Our Pencils</p>
                      </div>
                    </div>
                    <div class="grid grid-cols-3 gap-8">
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 1.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 2.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 3.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div :class="{'hidden': openTab !== 2, 'block': openTab === 2}">
                <div class="grid grid-cols-3 gap-4">
                  <div>
                    <p class="text-xl font-semibold p-8">
                      Graphite Artist Quality Fine Art Drawing and Sketching Pencils Replaceable Nib Pencils.
                    </p>
                    <ul class="list-block px-8">
                      <li>MECHANICAL PENCILS</li>
                      <li>ARCHITECT'S CHOICE</li>
                      <li>EXECUTIVE PENCILS</li>
                      <li>ENGRAVABLE PENCILS</li>
                    </ul>
                    <button class="py-3.5 px-6 bg-[#F4B840] rounded-md text-sm font-bold text-white  mt-9 ml-8">
                      SHOP ALL
                    </button>
                  </div>
                  <div class="col-span-2">
                    <div class="grid grid-cols-4 gap-8 bg-white rounded-2xl mb-4">
                      <div class="custom-sale flex justify-center">
                        <h2 class="text-[#F4B840]">
                          90% off
                        </h2>
                      </div>
                      <div class="custom col-span-3 ">
                        <p>Offer Applicable on All Our Pencils</p>
                      </div>
                    </div>
                    <div class="grid grid-cols-3 gap-8">
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 1.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 2.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 3.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div :class="{'hidden': openTab !== 3, 'block': openTab === 3}">
                <div class="grid grid-cols-3 gap-4">
                  <div>
                    <p class="text-xl font-semibold p-8">
                      Graphite Artist Quality Fine Art Drawing and Sketching Pencils Replaceable Nib Pencils.
                    </p>
                    <ul class="list-block px-8">
                      <li>MECHANICAL PENCILS</li>
                      <li>ARCHITECT'S CHOICE</li>
                      <li>EXECUTIVE PENCILS</li>
                      <li>ENGRAVABLE PENCILS</li>
                    </ul>
                    <button class="py-3.5 px-6 bg-[#F4B840] rounded-md text-sm font-bold text-white  mt-9 ml-8">
                      SHOP ALL
                    </button>
                  </div>
                  <div class="col-span-2">
                    <div class="grid grid-cols-4 gap-8 bg-white rounded-2xl mb-4">
                      <div class="custom-sale flex justify-center">
                        <h2 class="text-[#F4B840]">
                          50% off
                        </h2>
                      </div>
                      <div class="custom col-span-3 ">
                        <p>Offer Applicable on All Our Pencils</p>
                      </div>
                    </div>
                    <div class="grid grid-cols-3 gap-8">
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 1.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 2.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 3.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div :class="{'hidden': openTab !== 4, 'block': openTab === 4}">
                <div class="grid grid-cols-3 gap-4">
                  <div>
                    <p class="text-xl font-semibold p-8">
                      Graphite Artist Quality Fine Art Drawing and Sketching Pencils Replaceable Nib Pencils.
                    </p>
                    <ul class="list-block px-8">
                      <li>MECHANICAL PENCILS</li>
                      <li>ARCHITECT'S CHOICE</li>
                      <li>EXECUTIVE PENCILS</li>
                      <li>ENGRAVABLE PENCILS</li>
                    </ul>
                    <button class="py-3.5 px-6 bg-[#F4B840] rounded-md text-sm font-bold text-white  mt-9 ml-8">
                      SHOP ALL
                    </button>
                  </div>
                  <div class="col-span-2">
                    <div class="grid grid-cols-4 gap-8 bg-white rounded-2xl mb-4">
                      <div class="custom-sale flex justify-center">
                        <h2 class="text-[#F4B840]">
                          30% off
                        </h2>
                      </div>
                      <div class="custom col-span-3 ">
                        <p>Offer Applicable on All Our Pencils</p>
                      </div>
                    </div>
                    <div class="grid grid-cols-3 gap-8">
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 1.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 2.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class="flex justify-center bg-white rounded-2xl">
                        <div class="inner-box">
                          <div class="product-image">
                            <div class="pt-2.5 pb-3.5">
                              <img src="images/pen-img11 3.png" alt="">
                            </div>
                          </div>
                          <div class="product-infor">
                            <h4 class="text-center pb-2">
                              <a href="#">Aero Mechanical Pencil</a>
                            </h4>
                            <div class="flex justify-around pb-9">
                              <p class="price-final">
                                <span>$99.00</span>
                              </p>
                              <p class="price">
                                <span>$125.00</span>
                              </p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div slot="pagination" class="swiper-pagination" />
  </div>
</template>

<script>

export default {
  data () {
    return {
      openTab: 1
    }
  },
  methods: {
    toggleTabs (tabNumber) {
      this.openTab = tabNumber
    }
  }
}
</script>
<style scoped>
.swiper {
  max-width: 600px;
  height: 300px;
}

.swiper-slide {
  display: flex;
  justify-content: center;
  align-items: center;
}
.custom{
border-top-right-radius: 16px;
border-bottom-right-radius: 16px;
background: #F4F4F4;
padding: 30px;
border: 3px white solid;
font-weight: 300;
font-size: 25px;
color: #000000;
}
.custom-sale{
  font-weight: 700;
  margin: auto;
font-size: 36px;
color: #F4B840;
}
.box-shadow{
  background: #FFFFFF;
box-shadow: 0px 0px 27px rgba(0, 0, 0, 0.05);
border-radius: 10px;
}
.list-block{
  list-style-type: circle;
}
.list-block li{
  font-weight: 600;
font-size: 18px;
}
p.text-xl.font-semibold.p-8 {
    font-weight: 400;
    font-size: 21px;
}
.title-product{
  font-weight: 500;
font-size: 14px;
}
.price-final span{
  font-weight: 600;
font-size: 16px;
line-height: 24px;
color:black;
}
.price span{
  font-weight: 400;
font-size: 14px;
line-height: 21px;
color: #727272;

}
li.-mb-px.last\:mr-0.flex-auto.text-center.text-black.bg-\[\#f4f4f4\] {
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
}
</style>
