<template>
    <div>
        <section class="hero" style="margin-top: 11rem;">
            <div class="container">
                
                <div class="hero-content pb-5 text-center">
                <h1 class="hero-heading mb-0">Customer zone</h1>
                </div>
            </div>
            </section>
            <!-- customer login-->
            <section>
            <div class="container">
                <div class="row justify-content-center">
                <div class="col-lg-5">
                    <div class="block">
                    <div class="block-header">
                        <h6 class="text-uppercase mb-0">Iniciar sesión</h6>
                    </div>
                    <div class="block-body">
                   
                        <p class="text-muted">Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo.</p>
                        <hr>
                        <form action="customer-orders.html" method="get">
                        <div class="mb-4">
                            <label class="form-label" for="email1">Correo electrónico</label>
                            <input class="form-control" id="email1" type="text" placeholder="Correo electrónico" autocomplete="off">
                        </div>
                        <div class="mb-4">
                            <label class="form-label" for="password1">Contraseña</label>
                            <input class="form-control" id="password1" type="password" placeholder="Contraseña" autocomplete="off">
                        </div>
                        <div class="mb-4 text-center">
                            <button class="btn btn-outline-dark" type="button"><i class="fa fa-sign-in-alt me-2"></i> Ingresar</button>
                        </div>
                        </form>
                    </div>
                    </div>
                </div>
                <div class="col-lg-5">
                    <div class="block">
                    <div class="block-header">
                        <h6 class="text-uppercase mb-0">Nueva cuenta</h6>
                    </div>
                    <div class="block-body"> 
                     
                        <p class="text-muted">With registration with us new world of fashion, fantastic discounts and much more opens to you! The whole process will not take you more than a minute!</p>
                    
                        <form action="customer-orders.html" method="get">
                        <div class="mb-4">
                            <label class="form-label" for="name">Nombres completos</label>
                            <input class="form-control" id="name" type="text" placeholder="Nombres completos">
                        </div>
                        <div class="mb-4">
                            <label class="form-label" for="email">Correo electrónico</label>
                            <input class="form-control" id="email" type="text" placeholder="Correo electrónico">
                        </div>
                        <div class="mb-4">
                            <label class="form-label" for="password">Contraseña</label>
                            <input class="form-control" id="password" type="password" placeholder="Contraseña">
                        </div>
                        <div class="mb-4 text-center">
                            <button class="btn btn-outline-dark" type="button"><i class="far fa-user me-2"></i>Registrar                                </button>
                        </div>
                        </form>
                    </div>
                    </div>
                </div>
                </div>
            </div>
            </section>
    </div>
</template>

<script>
export default {
    name: 'LoginApp'
}
</script>