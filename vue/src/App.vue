<template>
  <div class="container">
    <h1>Açılır Kutu (Modal)</h1>
		<hr>


    <button type="button" class="btn btn-success" data-toggle="modal" data-target="#modal1">Modal Aç</button>

    <div class="modal fade" id="modal1">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Udemy Bootstrap Kursu</h5>
            <button type="button" class="close" data-dismiss="modal">
              <span>&times;</span>
            </button>
          </div>

          <div class="modal-body">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
            proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          </div>

          <div class="modal-footer">
            <button type="button" class="btn btn-success">Kaydet</button>
            <button type="button" class="btn btn-danger" data-dismiss="modal" >Çık</button>

          </div>
        </div>
      </div>
    </div>

    <hr>

    <h4>Form Özellikleri</h4>

    <button type="button" class="btn btn-success" data-toggle="modal" data-target="#modal2">Modal Aç</button>

    <div class="modal fade bd-example-modal-sm" id="modal2">
      <div class="modal-dialog modal-sm">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Udemy Bootstrap Kursu</h5>
            <button type="button" class="close" data-dismiss="modal">
              <span>&times;</span>
            </button>
          </div>

          <div class="modal-body">
         <div class="form-group">
           <label class="form-control-label">Adınız</label>
           <input type="text" class="form-control" placeholder="Adınız" name="">
         </div>
         <div class="form-group">
           <label class="form-control-label">Soyadınız</label>
           <input type="text" class="form-control" placeholder="Soyadınız" name="">
         </div>
          </div>

          <div class="modal-footer">
            <button type="button" class="btn btn-success">Kaydet</button>
            <button type="button" class="btn btn-danger" data-dismiss="modal" >Çık</button>

          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>

</script>

<style scoped>

</style>

