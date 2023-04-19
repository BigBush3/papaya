<template>
      <button 
            class="btn btn-primary"
    data-bs-target="#exampleModalToggle3"
    data-bs-toggle="modal"
    data-bs-dismiss="modal"
              style="
                width: 93%;
                height: 64px;
                background: #1d2024;
                border-radius: 35px;
                color: #ffffff;
              "
            >
              <p
                style="
                  font-style: normal;
                  font-weight: 500;
                  font-size: 22px;
                  line-height: 200%;
                  margin-top: 2%;
                "
              >
                Send
              </p>
            </button>

  <!-- Modal -->
  <div
    class="modal fade"
    id="exampleModal1"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div
        class="modal-content"
        style="
          width: 114%;
          height: 423.13px;
          background: #ffffff;
          box-shadow: 0px 0px 35px rgba(0, 0, 0, 0.2);
          border-radius: 50px;
        "
      >
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
            style="margin-right: 10px;margin-top: 1%;"
          ></button>
        </div>
        <div class="modal-body" style="">
          <div class="container">
            <div
              style="
                margin-left: 1%;
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <h1>Create an account</h1>
            </div>
            <div style="margin-left: 33%">
              <p
                style="
                  font-style: normal;
                  font-weight: 300;
                  font-size: 16px;
                  line-height: 120%;
                "
              >
                Please select your role:
              </p>
            </div>
            <div class="" style="margin-left: 12%">
              <div style="">
                <button
                  style="
                     width: 87%;
                    height: 64px;
                    background: #ffffff;
                    border: 1px solid #1d2024;
                    border-radius: 35px;
                  "
                >
                  <p
                    style="
                      font-style: normal;
                      font-weight: 500;
                      font-size: 22px;
                      line-height: 200%;
                      margin-top: 2%;
                    "
                  >
                    Client
                  </p>
                </button>
              </div>
              <div style="margin-top: 3%">
                <button
                  style="
                   width: 87%;
                    height: 64px;
                    background: #ffffff;
                    border: 1px solid #1d2024;
                    border-radius: 35px;
                    display: flex;
                    justify-content: center;
                  "
                >
                  <p  style="
                      font-style: normal;
                      font-weight: 500;
                      font-size: 22px;
                      line-height: 200%;
                      margin-top: 2%;
                    ">Service Provider</p>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
  export default{
    na
  }
</script>


<style>

</style>