<p align="center">
  <a href="https://getstisla.com">
    <img src="https://www.posciety.com/file/CodeIgniter-1024x576.png" alt="Codeigniter logo" width="75" height="75">
  </a>
</p>

<h1 align="center">Presence Using CodeIgniter</h1>

<p align="center">
  This presence uses the Stisla Bootstrap Admin Template and will help you make a presence.
</p>

[![Presence Preview](https://i.ibb.co/tPxzNmd/Presence.png)](https://presensi.ipdn.ac.id)

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
