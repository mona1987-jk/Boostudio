<template>
  <!-- Footer -->
  <mdb-footer color="unique-color-dark" class="page-footer font-small pt-0">
    <mdb-container class="mt-5 mb-4 text-center text-md-left">
      <mdb-row class="mt-3">
        <mdb-col md="3" lg="4" xl="3" class="mb-4">
          <h6 class="text-uppercase font-weight-bold"><strong>Company name</strong></h6>
          <hr class="deep-purple accent-2 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px" />
          <p>Here you can use rows and columns here to organize your footer content. Lorem ipsum dolor sit
            amet, consectetur adipisicing elit.</p>
        </mdb-col>
        <mdb-col md="2" lg="2" xl="2" class="mb-4">
          <h6 class="text-uppercase font-weight-bold"><strong>Products</strong></h6>
          <hr class="rgba-deep-orange-light  mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;color: chocolate" />
          <p><a href="#!">About us</a></p>
          <p><a href="#!">lorem </a></p>
          <p><a href="#!">BrandFlow</a></p>
          <p><a href="#!">Bootstrap Angular</a></p>
        </mdb-col>
        <mdb-col md="3" lg="2" xl="2" class="mb-4">
          <h6 class="text-uppercase font-weight-bold"><strong>Useful links</strong></h6>
          <hr class="deep-orange accent-2 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px" />
          <p><a href="#!">Your Account</a></p>
          <p><a href="#!">Become an Affiliate</a></p>
          <p><a href="#!">Shipping Rates</a></p>
          <p><a href="#!">Help</a></p>
        </mdb-col>
        <mdb-col md="4" lg="3" xl="3" class="mb-4">
          <h6 class="text-uppercase font-weight-bold"><strong>Contact</strong></h6>
          <hr class="deep-orangeaccent-2 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px" />
          <p><i class="fas fa-home mr-3"></i> Austrailia, NY 10012, US</p>
          <p>  <b-icon icon="envelope-fill"></b-icon>&nbsp;info@example.com</p>
          <p><b-icon icon="telephone-fill"></b-icon> + 01 234 567 88</p>
          <p><b-icon icon="phone"></b-icon> + 01 234 567 89</p>
        </mdb-col>
      </mdb-row>
    </mdb-container>
    <div class="footer-copyright text-center py-3">
      <mdb-container fluid>
        &copy; 2020 Copyright: <a href="https://www.MDBootstrap.com"> @Mona </a>
      </mdb-container>
    </div>
  </mdb-footer>
  <!-- Footer -->
</template>
<script>
    import { mdbFooter, mdbContainer, mdbRow, mdbCol } from 'mdbvue';
    export default {
        name: 'footer',
        components: {
            mdbFooter,
            mdbContainer,
            mdbRow,
            mdbCol
        }
    }
</script>



<style scoped>
  .page-footer{background-color: #0d0d0d;
  color:#878889;}
  .page-footer a{
    color:#878889;}
  .page-footer hr{color:#cf551c;
  }
  .page-footer h6{margin-top:35px;
  color: #cf551c;}
</style>
