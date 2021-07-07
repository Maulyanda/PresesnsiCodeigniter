<p align="center">
  <a href="https://getstisla.com">
    <img src="https://www.posciety.com/file/CodeIgniter-1024x576.png" alt="Codeigniter logo" width="75" height="75">
  </a>
</p>

<h1 align="center">Presence Using CodeIgniter</h1>

<p align="center">
  This presence uses the Stisla Bootstrap Admin Template and will help you make a presence.
</p>

[![Stisla Preview](https://camo.githubusercontent.com/2135e0f6544a7286a3412cdc3df32d47fc91b045/68747470733a2f2f692e6962622e636f2f3674646d6358302f323031382d31312d31312d31352d33352d676574737469736c612d636f6d2e706e67)](https://getstisla.com)

## Installation
- Clone the repo :
```
https://github.com/Maulyanda/PresesnsiCodeigniter.git
```

## Usage
- Create a new Controller at `application/controllers` then put like this:
```
<?php
defined('BASEPATH') OR exit('No direct script access allowed');

class Controller_name extends CI_Controller {

	public function index() {
		$data = array(
			'title' => "Your title"
		);
		$this->load->view('View_name', $data);
	}
}
?>
```
- Create a new View at `application/views` then put like this:
```
<?php
defined('BASEPATH') OR exit('No direct script access allowed');
$this->load->view('dist/_partials/header'); ?>

      <!-- Main Content -->

<?php
$this->load->view('dist/_partials/footer'); ?>
```

## License

Stisla is under the [MIT License](LICENSE).
