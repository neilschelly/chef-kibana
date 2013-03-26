## v0.1.4:

* Fixed permissions for KibanaConfig.rb so that the kibana user can read it.
  Used to be root:root, now uses the :user and :group attributes (nschelly)
* Adjusting command to ensure the proper version of ruby is used to execute
  Kibana in the init script.  gems are installed for ruby1.9.1, so the daemon
  startup command will force using ruby1.9.1 too now, but 1.9.1 is an attribute
  so that it can be changed in one place as necessary. (nschelly)

## v0.1.2:

* Prefer new notification syntax.

## v0.1.0:

* Initial release
