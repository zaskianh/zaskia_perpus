<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-4">
                    <h2 class="text-center my-4">buku</h2>
                    <div class="my-3">
                        <input type="search" class="form-control rounded-5" placeholder="Mau baca apa hari ini?"> </div>
                    <div class="my-3 text-muted">menampilkan 3 dari 3</div>
                </div>
            </div>
        <div class="row">
            <div class="col-lg-2">
                <div class="card mb-3 cover">
                    <div class="card-body">
                        <img src="/asset/img/novel1.jpg" class="novel" alt="novel1">
                    </div>
                </div>
            </div>
            <div class="col-lg-2">
                <div class="card mb-3 cover">
                    <div class="card-body">
                        <img src="/asset/img/novel2.jpg" class="novel" alt="novel2">
                    </div>
                </div>
            </div>
            <div class="col-lg-2">
                <div class="card mb-3 cover">
                    <div class="card-body">
                        <img src="/asset/img/novel3.jpg" class="novel" alt="novel3">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template> 

<style scoped>
.card-body {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: 0 30;
    /* margin-right: 200px; */
    padding: 0;
}
img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: 0 30;
    
}

</style>

