For our grid we are using the [Bootstrap Grid System](http://getbootstrap.com/css/#grid). Follow their [guide](http://getbootstrap.com/css/#grid) for implementation.

**Important**: Content should be placed within columns, and only columns may be immediate children of rows.

**Bad**
```
<div class="row">
  <div class="bad-div">
    <div class="col-md-6>
      <p>Width of 50% on medium screens</p>
    </div>
    <div class="col-md-6>
      <p>Width of 50% on medium screens</p>
    </div>
  </div>
</div>
```

**Good**
```
<div class="row">
  <div class="col-sm-12">
    <p>Bad Content</p>
  </div>
</div>
<div class="row">
    <div class="col-md-6>
      <p>Width of 50% on medium screens</p>
    </div>
    <div class="col-md-6>
      <p>Width of 50% on medium screens</p>
    </div>
</div>
```