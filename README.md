# UI - TRICKS
Simple html and css trciks to handle particular html design scenario

## Place an icon inside input box
 ```bash
<div class="input-group">
  <span>
    <i class="fa fa-user-circle-o" aria-hidden="true"></i>
  </span>
  <input type="text" class="form-control" placeholder="Username" />
</div>
 ```
 ```bash
input{
  border:none;
  background-color: transparent;
}
input:focus,
select:focus,
textarea:focus,
button:focus {
    outline: none;
}

.fa-user-circle-o{
  color: gray;
}

.input-group{
  border: 1px gray solid;
  padding: 10px;
}
 ```

 ## what's next?