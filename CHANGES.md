# Changes History

1.2.0
-----
Add new class CamelCaseModel extends Model.
This class make easy work with DB tables named by camel case notation.

1.1.4
-----
Fix User::getFullName() - trim whitespaces

1.1.3
-----
User implements JWTSubject

1.1.2
-----
User->hasVerifiedEmail() takes into consideration local constant

1.1.1
-----
* Add Email verification to user model
* Change const User::AVATAR_URL to User::AVATAR
* Fix namespace in MediableTrait 

1.1.0
-----
Declare Laravel 6 compatibility

1.0.8
-----
* Enable Laravel's package discovery https://laravel.com/docs/5.5/packages#package-discovery
* Deprecate User->getRules() method.
  Declare your rules in form request validation instead: https://laravel.com/docs/5.5/validation#form-request-validation

1.0.7
-----
Add SortByName QueryBuilder global scope

1.0.6
-----
* User model utilizes Authorizable trait
* Add base job class, queueable by default

1.0.5
-----
Class Saritasa\Database\Eloquent\Utils\Query with helper functions to work with Eloquent queries

1.0.4
-----
Remove User->setProfileVisible method and two sets of visible fields. Should be done via Transformer

1.0.3
-----
* Update User model to use saritasa/roles-simple
* Publish migrations in console only

1.0.2
-----
Fix namespace, remove unneeded migrations

1.0.1
-----
Fixes

1.0.0
-----
Initial version: Entity inheritor for Eloquent Model. Allows to set default values.
