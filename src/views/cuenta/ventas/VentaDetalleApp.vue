<template>
    <div  style="background: #f3f3f3;" class="pb-5">
            <section class="hero" style="margin-top: 8rem !important;">
      <div class="container">
        <!-- Breadcrumbs -->
         <ol class="breadcrumb justify-content-center">
            <li class="breadcrumb-item"><router-link to="/">Home</router-link></li>
            <li class="breadcrumb-item"><router-link to="/">Mis ventas</router-link></li>
            <li class="breadcrumb-item active">Orden #123        </li>
            </ol>
        <!-- Hero Content-->
        <div class="hero-content pb-5 text-center">
          <h1 class="hero-heading">Order #1735</h1>
          <div class="row">   
            <div class="col-xl-8 offset-xl-2"><p class="lead text-muted">Order #1735 was placed on <strong>22/06/2021</strong> and is currently <strong>Being prepared</strong>.</p><p class="text-muted">If you have any questions, please feel free to <a href="contact.html">contact us</a>, our customer service center is working for you 24/7.</p></div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-lg-8 col-xl-9">
            <div class="cart">
              <div class="cart-wrapper">
               <div class="cart-header text-center" style="background: #2983df !important;">
                    <div class="row">
                    <div class="col-6">
                        <span class="text-left text-white">Producto</span>
                    </div>
                    <div class="col-2">
                        <span class="text-white">Precio</span>
                    </div>
                    <div class="col-2">
                        <span class="text-white">Cantidad</span>
                    </div>
                    <div class="col-2">
                        <span class="text-white">Total</span>
                    </div>
                    </div>
                </div>
                <div class="cart-body" style="background: #fff6e8 !important">
                  <!-- Product-->
                  <div class="cart-item">
                    <div class="row d-flex align-items-center text-center">
                      <div class="col-6">
                        <div class="d-flex align-items-center"><a href="detail.html"><img class="cart-item-img" src="https://d19m59y37dris4.cloudfront.net/sell/2-0/img/product/product-square-ian-dooley-347968-unsplash.jpg" alt="..."></a>
                          <div class="cart-title text-start"><a class="text-uppercase text-dark" href="detail.html"><strong>Skull Tee</strong></a><br><span class="text-muted text-sm">Size: Large</span><br><span class="text-muted text-sm">Colour: Green</span>
                          </div>
                        </div>
                      </div>
                      <div class="col-2">$65.00</div>
                      <div class="col-2">4
                      </div>
                      <div class="col-2 text-center">$260.00</div>
                    </div>
                  </div>
                  <!-- Product-->
                  <div class="cart-item">
                    <div class="row d-flex align-items-center text-center">
                      <div class="col-6">
                        <div class="d-flex align-items-center"><a href="detail.html"><img class="cart-item-img" src="https://d19m59y37dris4.cloudfront.net/sell/2-0/img/product/product-square-kyle-loftus-596319-unsplash.jpg" alt="..."></a>
                          <div class="cart-title text-start"><a class="text-uppercase text-dark" href="detail.html"><strong>Transparent Blouse</strong></a><br><span class="text-muted text-sm">Size: Medium</span>
                          </div>
                        </div>
                      </div>
                      <div class="col-2">$55.00</div>
                      <div class="col-2">3
                      </div>
                      <div class="col-2 text-center">$165.00</div>
                    </div>
                  </div>
                  <!-- Product-->
                  <div class="cart-item">
                    <div class="row d-flex align-items-center text-center">
                      <div class="col-6">
                        <div class="d-flex align-items-center"><a href="detail.html"><img class="cart-item-img" src="https://d19m59y37dris4.cloudfront.net/sell/2-0/img/product/product-square-serrah-galos-494312-unsplash.jpg" alt="..."></a>
                          <div class="cart-title text-start"><a class="text-uppercase text-dark" href="detail.html"><strong>White Tee</strong></a><br><span class="text-muted text-sm">Size: Medium</span>
                          </div>
                        </div>
                      </div>
                      <div class="col-2">$55.00</div>
                      <div class="col-2">3
                      </div>
                      <div class="col-2 text-center">$165.00</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="row my-5">
              <div class="col-md-6">
                <div class="block mb-5" >
                  <div class="block-header" style="background: #fff6e8 !important">
                    <h6 class="text-uppercase mb-0">Order Summary</h6>
                  </div>
                  <div class="block-body bg-light pt-1" style="background: #fff6e8 !important">
                    <p class="text-sm">Shipping and additional costs are calculated based on values you have entered.</p>
                    <ul class="order-summary mb-0 list-unstyled">
                      <li class="order-summary-item"><span>Order Subtotal </span><span>$390.00</span></li>
                      <li class="order-summary-item"><span>Shipping and handling</span><span>$10.00</span></li>
                      <li class="order-summary-item"><span>Tax</span><span>$0.00</span></li>
                      <li class="order-summary-item border-0"><span>Total</span><strong class="order-summary-total">$400.00</strong></li>
                    </ul>
                  </div>
                </div>
              </div>
              <div class="col-md-6">
                <div class="block-header" style="background: #fff6e8 !important">
                  <h6 class="text-uppercase mb-0">Invoice address</h6>
                </div>
                <div class="block-body bg-light pt-1" style="background: #fff6e8 !important">
                  <p>John Brown<br>13/25 New Avenue<br>New Heaven<br>45Y 73J<br>England<br><strong>Great Britain</strong></p>
                </div>
                <div class="block-header" style="background: #fff6e8 !important">
                  <h6 class="text-uppercase mb-0">Shipping address</h6>
                </div>
                <div class="block-body bg-light pt-1" style="background: #fff6e8 !important">
                  <p>John Brown<br>13/25 New Avenue<br>New Heaven<br>45Y 73J<br>England<br><strong>Great Britain</strong></p>
                </div>
              </div>
            </div>
          </div>
          <!-- Customer Sidebar-->
          <div class="col-xl-3 col-lg-4 mb-5">
              <SidebarCliente/>
          </div>
          <!-- /Customer Sidebar-->
        </div>
      </div>
    </section>
    </div>
</template>

<script>
import SidebarCliente from '@/components/SidebarCliente.vue';

export default {
    name: 'VentaDetalleApp',
    components: {
      SidebarCliente
    }
}
</script>