<template>
  <div class="about">
    <h1>This is an sign in page</h1>
    <div class="container">
      <div class="row">
        <div class="col-sm"></div>
        <div class="col-sm">
          <form>
            <div class="form-group">
              <label>Ime</label>
              <input
                type="email"
                class="form-control"
                placeholder="Unesi ime"
              />
            </div>
            <div class="form-group">
              <label>Prezime</label>
              <input class="form-control" placeholder="Prezime" />
            </div>

            <div class="form-group">
              <label for="exampleInputEmail1">Email</label>
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Unesi email"
              />
            </div>
            <div class="form-group">
              <label for="exampleInputPassword1">Unesi lozinku</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Lozinka"
              />
            </div>
            <div class="form-group">
              <label for="exampleInputPassword1">Potvrdi lozinku</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Lozinka"
              />
            </div>
            <button type="Sign up" class="btn btn-primary">Sign up</button>
          </form>
        </div>
        <div class="col-sm"></div>
      </div>
    </div>
  </div>
</template>