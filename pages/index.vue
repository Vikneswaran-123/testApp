<template>
  <div class="bg-gray-100 w-screen h-screen">
    <div class="flex flex-row justify-center place-content-center h-screen">
      <div class="m-5">
        <div class="pt-2">
          <div class="">
            <label for="Variant">Brand</label>
          </div>
          <div class="pt-2">
            <select id="bike brand" class="border-2 w-40" name="bike">
              <option value="volvo">Kawasaki</option>
              <option value="saab">Bajaj</option>
              <option value="mercedes">Honda</option>
              <option value="audi">Yamaha</option>
            </select>
          </div>
        </div>
        <div class="pt-2">
          <div class="">
            <label for="Model">MODEL</label>
          </div>
          <div class="pt-2">
            <select id="bike name" class="border-2 w-40" name="bike">
              <option value="volvo">Ninja 250</option>
              <option value="saab">Pulsar220</option>
              <option value="mercedes">Yamaha R15</option>
              <option value="audi">Honda CBR</option>
            </select>
          </div>
        </div>
        <div class="pt-2">
          <div>
            <label for="Variant">Variant</label>
          </div>
          <div class="pt-2">
            <select id="variant name" class="border-2 w-40" name="bike">
              <option value="volvo">ABS</option>
              <option value="saab">NON-ABS</option>
            </select>
          </div>
        </div>
        <div class="pt-2">
          <div>
            <label for="Fittings">Fittings</label>
          </div>
          <div class="pt-2">
            <select id="extra fittings" class="border-2 w-40" name="bike">
              <option value="volvo">Horn</option>
              <option value="saab">Engine Guard</option>
              <option value="mercedes">Seat cover</option>
              <option value="audi">Tankpad</option>
            </select>
          </div>
        </div>
        <div class="pt-2">
          <div>
            <label for="Finance Scheme">Finance Scheme</label>
          </div>
          <div class="pt-2">
            <select id="bike finance" class="border-2 w-40" name="bike">
              <option value="volvo">Bajaj Finserv</option>
              <option value="saab">HDFC Bike Scheme</option>
              <option value="mercedes">ICICI Bank</option>
            </select>
          </div>
        </div>
      </div>
      <div class="m-5">
        <div class="my-5 w-44 h-32">
          <img class="" src="https://i.imgur.com/9348Hp0.png" alt="" />
        </div>
        <div>
          <div><label for="price model">Price</label></div>
          <div>
            <input class="border-2" type="text" />
          </div>
        </div>
        <div>
          <div><label for="price fitting">Price fittings</label></div>
          <div>
            <input class="border-2" type="text" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
