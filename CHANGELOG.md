### 0.6.0
* Remove typing library for Python 3.5+
* Made get and post methods abstract to allow custom implementations
### 0.5.2
* Remove some workaround due to Somfy limitation
* Allow to provide state during OAuth process
### 0.5.1
*  Made redirect uri optional
### 0.5.0
* Expose token updater method
* Remove default token updater (token save as file)
### 0.4.4
* Use get_state method to get blind orientation
* Set 0 as orientation when not available for the blind
### 0.4.3
* Token can now be fetch using the code instead of the full authorization response
### 0.4.2
* Raise an HTTPError when Somfy API returns a status code not ok 
### 0.4.1
* Fix command always rejected
### 0.4.0
* Implicit automatic token refresh
### 0.3.2
* Fix Thermostat class name
### O.3.0
* Add thermostat support
* Add camera support
* Add low speed support for roller shutters
* roller shutter position is no more a property
### 0.2.2
* Add orientation support for blind
### 0.2.1
* Fix package generation
### 0.2.0
* Add blind support
### 0.1.0
* Add support for roller shutters