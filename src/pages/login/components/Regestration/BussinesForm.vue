<template>
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
          <h5
            class="modal-title"
            id="exampleModalLabel"
            style="
              font-style: normal;
              font-weight: 400;
              font-size: 14px;
              line-height: 120%;
              /* identical to box height, or 17px */

              display: flex;
              align-items: center;
              margin-top: 2%;
              margin-left: 2%;
              color: #989fa1;
            "
          >
            Back
          </h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
            style="margin-right: 4.5%; margin-top: 1%"
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
                   class="btn btn-primary"
                  data-bs-target="#exampleModal4"
                  data-bs-toggle="modal"
                  data-bs-dismiss="modal"

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
                    Company
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
                  <p
                    style="
                      font-style: normal;
                      font-weight: 500;
                      font-size: 22px;
                      line-height: 200%;
                      margin-top: 2%;
                    "
                  >
                    Freelancer
                  </p>
                </button>
                <div style="margin-top: 3%">
                  <button
                    style="
                      width: 87%;
                      height: 30%;
                      background: #ffffff;
                      border: 1px solid #1d2024;
                      border-radius: 35px;
                      display: flex;
                      justify-content: center;
                      max-width: 428px;
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
                      Language Service Provider
                    </p>
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
</script>
<style>
</style>