# ci3-dasboard

```php
public function index()
{
    // load view admin/overview.php
    $this->load->view("admin/overview");
}
```
- `setting_top.php`
```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<?php $this->
		load->view("admin/_partials/head.php") ?>
	</head>

	<body id="page-top">
		<?php $this->load->view("admin/_partials/navbar.php") ?>
		<div id="wrapper">
			<?php $this->load->view("admin/_partials/sidebar.php") ?>
			<div id="content-wrapper"></div>
		</div>
```

- `overview.php`
```html
<?php $this->load->view("admin/_partials/setting_top.php") ?>

<div class="container-fluid">

    <?php $this->load->view("admin/_partials/breadcrumb.php") ?>
    
</div>

<?php $this->load->view("admin/_partials/setting_bottom.php") ?>
```

- `setting_bottom.php`
```html
            <?php $this->load->view("admin/_partials/footer.php") ?>
        </div>
    </div>
    <?php $this->load->view("admin/_partials/scrolltop.php") ?>
    <?php $this->load->view("admin/_partials/modal.php") ?>
    <?php $this->load->view("admin/_partials/js.php") ?>
</body>

</html>
```

![](https://github.com/gzeinnumer/ci3-dasboard/blob/master/preview/example1.jpg)

Only Design

---

```
Copyright 2021 M. Fadli Zein
```