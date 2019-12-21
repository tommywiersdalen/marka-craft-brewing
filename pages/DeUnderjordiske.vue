<template>
  <div>
    <div class="row">
      <div class="col productMain">
        <div class="row">
          <div class="col ProductContent">
            <h4>De Underjordiske</h4
            >
            <p>
              <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/The_changeling%2C_John_Bauer%2C_1913.jpg" class="productImage" alt="">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi cupiditate eos cum quo autem facilis eius, soluta expedita nisi, libero dignissimos quos earum tempora fuga vitae in quae? Excepturi, pariatur?
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum modi sed accusantium suscipit earum eaque excepturi eius distinctio. Dolorem deleniti tempore ad hic facilis ex beatae, similique provident laboriosam reiciendis!
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptate laboriosam vitae recusandae placeat ratione ex accusamus illum dolorum deserunt iusto doloremque eaque illo ipsam, consequatur nesciunt dicta dolor quisquam. Corrupti?
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus quasi inventore sapiente beatae minima consequuntur voluptatibus adipisci, quam corporis illo ratione tempore. Aut modi quos ullam cum tempore quaerat ipsam.
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde cum at iure qui. Ratione quisquam delectus ipsa dicta! Nesciunt fuga perspiciatis quod natus tempore optio eaque deleniti est, illum delectus?
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit perferendis harum quasi qui laboriosam distinctio pariatur esse sunt laborum excepturi illo minus unde in eveniet, accusamus autem, expedita, fuga error.
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit error fugiat quis? Ad aliquid, cumque eos, quod provident aliquam illo harum necessitatibus quo praesentium corporis saepe, ullam sed. Obcaecati, assumenda.
            </p>
              <div class="row InfoDivider">
              <div class="col-4 ProductContent">ABV: 8%</div>
              <div class="col-4 ProductContent">IBU:30°</div>
              <div class="col-4 ProductContent">330ML</div>
              </div>
          </div>
        </div>
        <div class="row">
          <div class="col"></div>
        </div>
        <div class="row">
          <div class="col"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@media (max-width: 991px) {
  .productImage{
    width: 100% !important;
    float: none !important;
    margin-bottom: 10px !important;
  }
  .productMain{
    margin: 0 !important;
  }
}
.productImage{
  width: 50%;
  float: left;
  margin-right: 20px;
  margin-top: 6px;


}
.productMain{
  background-color: rgba(73, 73, 73, 0.23);
  padding: 20px;
  margin-left: 240px;
  margin-right: 240px;
}

.ProductContent{
  padding: 0;
}
.InfoDivider {
  border-top: 2px dashed #1c1c1c;
  border-bottom: 2px dashed #1c1c1c;
}
</style>
