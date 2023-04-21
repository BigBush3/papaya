<template>
  <div class="modal-dialog">
    <div
      class="modal-content"
      style="
        width: 1052px;
        height: 1189.65px;
        background: #ffffff;
        box-shadow: 0px 0px 35px rgba(0, 0, 0, 0.2);
        border-radius: 50px;
      "
    >
      <div style="display: flex">
        <button class="btn btn-link" style="margin-left: 3%; margin-top: 3%">
          <p
            style="
              font-style: normal;
              font-weight: 400;
              font-size: 14px;
              line-height: 120%;
              /* identical to box height, or 17px */

              display: flex;
              align-items: center;

              color: #989fa1;
            "
          >
            Back
          </p>
        </button>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Close"
          style="margin-left: 86%; margin-top: 3%"
        ></button>
      </div>
      <div class="modal-body" style="">
        <div>
          <div style="display: flex; justify-content: center">
            <h1>Company Registration Form</h1>
          </div>
          <div style="display: flex; justify-content: center">
            <p
              style="
                font-style: normal;
                font-weight: 300;
                font-size: 16px;
                line-height: 120%;
              "
            >
              Please complete the form
            </p>
          </div>
          <div>
            <div class="accordion" id="accordionExample">
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button
                    class="accordion-button"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseOne"
                    aria-expanded="true"
                    aria-controls="collapseOne"
                  >
                    Accordion Item #1
                  </button>
                </h2>
                <div
                  id="collapseOne"
                  class="accordion-collapse collapse show"
                  data-bs-parent="#accordionExample"
                  style="width: 700px"
                >
                  <div class="accordion-body">
                    <div>
                      <p
                        style="
                          font-style: normal;
                          font-weight: 500;
                          font-size: 14px;
                          line-height: 120%;
                          /* identical to box height, or 17px */

                          display: flex;
                          align-items: center;
                          text-transform: uppercase;

                          color: #1d2024;
                        "
                      >
                        About Company
                      </p>
                    </div>
                    <div style="display: flex">
                      <div>
                        <label
                          for="exampleFormControlTextarea1"
                          class="form-label"
                          >Example textarea</label
                        >
                        <input
                          class="form-control"
                          id="exampleFormControlTextarea1"
                          placeholder="Please enter your company name"
                          style="
                            background: #f1f5f8;
                            border-radius: 10px;
                            width: 250%;
                            height: 56px;
                          "
                        />
                      </div>

                      <div style="margin-left: 42%;margin-top: 4.8%;">
                       
                       



                        <select
                          class="form-select"
                          aria-label="Default select example"
                          style=" background: #f1f5f8;
                            border-radius: 10px;
                            width: 190%;
                            height: 56px;"
                            
                        >
                        
                          <option selected>Please choose from the list below</option>
                          <option value="1">One</option>
                          
                        </select>
                      </div>
                    </div>
                    <div
                      style="
                        display: flex;

                        justify-content: center;

                        margin-top: 3%;
                      "
                    >
                      <button
                        style="
                          background: #ffffff;
                          border: 1px solid #1d2024;
                          border-radius: 35px;
                          width: 170px;
                          height: 44px;
                          margin-left: 30%;
                        "
                      >
                        Save
                      </button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseTwo"
                    aria-expanded="false"
                    aria-controls="collapseTwo"
                  >
                    Accordion Item #2
                  </button>
                </h2>
                <div
                  id="collapseTwo"
                  class="accordion-collapse collapse"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <strong>This is the second item's accordion body.</strong>
                    It is hidden by default, until the collapse plugin adds the
                    appropriate classes that we use to style each element. These
                    classes control the overall appearance, as well as the
                    showing and hiding via CSS transitions. You can modify any
                    of this with custom CSS or overriding our default variables.
                    It's also worth noting that just about any HTML can go
                    within the <code>.accordion-body</code>, though the
                    transition does limit overflow.
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseThree"
                    aria-expanded="false"
                    aria-controls="collapseThree"
                  >
                    Accordion Item #3
                  </button>
                </h2>
                <div
                  id="collapseThree"
                  class="accordion-collapse collapse"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <strong>This is the third item's accordion body.</strong> It
                    is hidden by default, until the collapse plugin adds the
                    appropriate classes that we use to style each element. These
                    classes control the overall appearance, as well as the
                    showing and hiding via CSS transitions. You can modify any
                    of this with custom CSS or overriding our default variables.
                    It's also worth noting that just about any HTML can go
                    within the <code>.accordion-body</code>, though the
                    transition does limit overflow.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>

<script></script>
