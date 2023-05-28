<template>
    <div style="background: #f3f3f3;" class="pb-5">
         <section class="hero"  style="margin-top: 8rem !important;">
            <div class="container">
                <!-- Breadcrumbs -->
                <ol class="breadcrumb justify-content-center">
                 <li class="breadcrumb-item"><router-link to="/">Home</router-link ></li>
                <li class="breadcrumb-item active">Mis compras        </li>
                </ol>
                <!-- Hero Content-->
                <div class="hero-content pb-5 text-center">
                <h1 class="hero-heading">Mis compras </h1>
                <div class="row">   
                    <div class="col-xl-8 offset-xl-2"><p class="lead">Your orders in one place.</p></div>
                </div>
                </div>
            </div>
            </section>
            <section>
            <div class="container">
                <div class="row">
                <div class="col-lg-8 col-xl-9">
                    <table class="table table-borderless table-hover table-responsive-md">
                    <thead class="bg-light">
                        <tr>
                        <th class="py-4 text-uppercase text-sm">Order #</th>
                        <th class="py-4 text-uppercase text-sm">Date</th>
                        <th class="py-4 text-uppercase text-sm">Total</th>
                        <th class="py-4 text-uppercase text-sm">Status</th>
                        <th class="py-4 text-uppercase text-sm">Action</th>
                        </tr>
                    </thead>
                    <tbody style="background: white !important;">
                        <tr>
                        <th class="py-4 align-middle"># 1735</th>
                        <td class="py-4 align-middle">22/6/2017</td>
                        <td class="py-4 align-middle">$150.00</td>
                        <td class="py-4 align-middle"><span class="badge p-2 text-uppercase badge-info-light">Being prepared</span></td>
                        <td class="py-4 align-middle"><a class="btn btn-outline-dark btn-sm" href="customer-order.html">View</a></td>
                        </tr>
                        <tr>
                        <th class="py-4 align-middle"># 1734</th>
                        <td class="py-4 align-middle">7/5/2017</td>
                        <td class="py-4 align-middle">$150.00</td>
                        <td class="py-4 align-middle"><span class="badge p-2 text-uppercase badge-warning-light">Action needed</span></td>
                        <td class="py-4 align-middle"><a class="btn btn-outline-dark btn-sm" href="customer-order.html">View</a></td>
                        </tr>
                        <tr>
                        <th class="py-4 align-middle"># 1730</th>
                        <td class="py-4 align-middle">30/9/2016</td>
                        <td class="py-4 align-middle">$150.00</td>
                        <td class="py-4 align-middle"><span class="badge p-2 text-uppercase badge-success-light">Received</span></td>
                        <td class="py-4 align-middle"><a class="btn btn-outline-dark btn-sm" href="customer-order.html">View</a></td>
                        </tr>
                        <tr>
                        <th class="py-4 align-middle"># 1705</th>
                        <td class="py-4 align-middle">22/6/2016</td>
                        <td class="py-4 align-middle">$150.00</td>
                        <td class="py-4 align-middle"><span class="badge p-2 text-uppercase badge-danger-light">Cancelled</span></td>
                        <td class="py-4 align-middle"><a class="btn btn-outline-dark btn-sm" href="customer-order.html">View</a></td>
                        </tr>
                    </tbody>
                    </table>
                </div>
                <!-- Customer Sidebar-->
                <div class="col-xl-3 col-lg-4 mb-5">
                    <SiderCliente/>
                </div>
                <!-- /Customer Sidebar-->
                </div>
            </div>
            </section>
    </div>
</template>

<style>
th.py-4.text-uppercase.text-sm {
    background: #2983df !important;
    color: white !important;
}
</style>
<script>
import SiderCliente from '@/components/SidebarCliente.vue';
export default {
    name: 'VentaIndexApp',
    components: {
        SiderCliente
    }
}
</script>