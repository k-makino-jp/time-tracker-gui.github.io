<template>
  <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-2 pb-2 mb-3 border-bottom">
    <h2>Usage</h2>
  </div>

  <div class="card mb-3">
    <div class="card-header">
      <h4>How to use Time Tracker?</h4>
    </div>
    <div class="card-body">
      <ol>
        <li>Access to Time Tracker.</li>
        <li>Enter or select your current task name.</li>
        <li>Press Start button.</li>
        <li>When you complete the task, press Stop button and time tracking process will be stopped.
        </li>
        <li>Back to 2.</li>
      </ol>
    </div>
  </div>

  <div class="card">
    <div class="card-header">
      <h4>How to delete unwanted autofill suggestions in Chrome?</h4>
    </div>
    <div class="card-body">
      <ol>
        <li>Highlight the suggestion you want to clear by hovering your mouse over it.</li>
        <li>Press the "SHIFT" and "DELETE" keys at the same time.</li>
      </ol>
    </div>
  </div>

</template>

<style scoped>
body {
  font-size: .875rem;
  background-color: #f8f8f8;
  padding-top: 50px;
}

.feather {
  width: 16px;
  height: 16px;
  vertical-align: text-bottom;
}

.card {
  border-radius: 0%;
}

.card-header {
  background-color: #fff;
}

.btn {
  border-radius: 0%;
}

.form-control {
  border-radius: 0%;
}

/*
   * Sidebar
   */

.sidebar {
  position: fixed;
  top: 48px;
  /* rtl:raw:
    right: 0;
    */
  bottom: 0;
  /* rtl:remove */
  left: 0;
  z-index: 100;
  /* Behind the navbar */
  padding: 0px 0 0;
  /* Height of navbar */
  box-shadow: inset -1px 0 0 rgba(0, 0, 0, .1);
}

@media (max-width: 767.98px) {
  .sidebar {
    top: 5rem;
  }
}

.list-group .list-group-item.sidebaritem {
  background-color: #e7e7e7;
  border-top-color: #e7e7e7;
  border-bottom-color: #e7e7e7;
  /* or whatever color you'd like */
}

.list-group .list-group-item.sidebaritem:hover {
  background-color: #c0c0c0;
  border-top-color: #e7e7e7;
  border-bottom-color: #e7e7e7;
  /* or whatever color you'd like */
}

.sidebar {
  background-color: #e7e7e7;
}

.sidebar-sticky {
  position: relative;
  top: 0;
  height: calc(100vh - 48px);
  padding-top: .5rem;
  overflow-x: hidden;
  overflow-y: auto;
  /* Scrollable contents if viewport is shorter than content. */
}

.sidebar .nav-link {
  font-weight: 500;
  color: #333;
}

.sidebar .nav-link .feather {
  margin-right: 4px;
  color: #727272;
}

.sidebar .nav-link.active {
  background-color: #cccccc;
  border-color: #acacac;
  border-top-color: #e7e7e7;
  border-bottom-color: #e7e7e7;
  /* border-left-color: #333;
  border-left-width: 4px; */
}

.sidebar .nav-link:hover .feather,
.sidebar .nav-link.active .feather {
  color: inherit;
}

/*
   * Navbar
   */

.navbar {
  background-color: #333;
}

.navbar-brand {
  padding-left: .2rem;
  padding-top: .75rem;
  padding-bottom: .75rem;
  font-size: 1rem;
}

.navbar .navbar-toggler {
  top: .25rem;
  right: 1rem;
}

.navbar .form-control {
  padding: .75rem 1rem;
  border-width: 0;
  border-radius: 0;
}

.form-control-dark {
  color: #fff;
  background-color: rgba(255, 255, 255, .1);
  border-color: rgba(255, 255, 255, .1);
}

.form-control-dark:focus {
  border-color: transparent;
  box-shadow: 0 0 0 3px rgba(255, 255, 255, .25);
}

.each-task-spend-time {
  font-family: SFMono-Regular;
}
</style>
