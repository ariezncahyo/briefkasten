## About Briefkasten

Briefkasten is a web application for manage SMS (Short Message Servcie) build from elegant framework Laravel. It use gammu-smsd (part of gammu family) as SMS gateway engine to deliver and retrieve messages from your phone/modem. We believe development must be an enjoyable and creative experience to be truly fulfilling. Briefkasten attempts to manage SMS, such as:

- Manage retreive message
- Manage sent message
- Manage out message
- Manage phobebooks 
- Support broadcast messages
- Support auto responder
- Support multiple modem

## Requirement

You need to install and configure this first:

* PHP >= 5.6.4
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* PHP-CLI
* composer
* MySQL 5.x.x or PostgreSQL or SQLite3
<pre>or you can just install xampp (http://www.apachefriends.org/en/xampp.html)</pre>
* gammu-smsd, make sure it is already running and configured


## Installation:  

1. Extract to web root folder (eq: /var/www/html => Ubuntu) or clone this repository
2. Intall using composer
    <pre>
        $ composer install
    </pre>
3. Create database (you can do it with mysql console or phpMyAdmin)
  * using mysql console
     <pre>
     # mysql > CREATE DATABASE <database name>;
     # mysql > quit
     </pre>
  * using phpMyAdmin
3. Edit database config (config/database.php) or edit .env file
4. Import gammu database schema
5. Run Migration
    <pre>
        $ php artisan migrate
    </pre>

## Contributing

Thank you for considering contributing to the Briefkasten!
You can contribute with Forking this repository.

## Security Vulnerabilities

If you discover a security vulnerability, please send an e-mail to Wahyu KecambahLinux at wahyu.kelix@gmail.com.

## License

The Briefkasten is open-sourced software licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
