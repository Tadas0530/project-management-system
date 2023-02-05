<template>
  <header class="p-3 red-color header-height">
    <div class="container-flex">
      <div class="d-flex flex-wrap align-items-center justify-content-between">
        <a
          href="/"
          class="
            d-flex
            align-items-center
            mb-2 mb-lg-0
            text-white text-decoration-none
          "
        >
          <svg
            class="bi me-2"
            width="40"
            height="32"
            role="img"
            aria-label="Bootstrap"
          >
            <use xlink:href="#bootstrap"></use>
          </svg>
        </a>

        <div
          class="
            nav
            col-12 col-lg-auto
            me-lg-auto
            mb-2
            align-items-center
            justify-content-center
            mb-md-0
          "
        >
          <font-awesome-icon icon="fa-solid fa-bars" />
          <font-awesome-icon icon="fa-solid fa-house" />
          <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
            <input
              type="search"
              class="form-control"
              placeholder="Search..."
              aria-label="Search"
            />
          </form>
        </div>

        <font-awesome-icon class="mr-5" icon="fa-solid fa-plus" />
        <font-awesome-icon icon="fa-solid fa-bell" />
        <font-awesome-icon icon="fa-solid fa-gear" />
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
.red-color {
  background-color: #dc4c41;
}

svg {
  font-size: larger;
  color: white;
  margin-right: 1.5rem;
}

input,
input:focus {
  background-color: #e36f66;
}

input::placeholder {
  color: white;
}
</style>