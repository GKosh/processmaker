---
description: >-
  Before installing ProcessMaker Spark on-premises, understand which
  technologies ProcessMaker requires.
---

# On-Premises Server Requirements

## On-Premises Server Requirements

{% hint style="info" %}
The following server requirements are only for ProcessMaker Spark on-premises installation. Since ProcessMaker Spark is primarily an Enterprise cloud solution, these server requirements do not apply to ProcessMaker Spark.
{% endhint %}

The following are server requirements to install ProcessMaker Spark on-premises:

* **Core server components:** Ensure your server has the following core components:
  * PHP 7.1.3 or later
  * Composer Dependency Manager for PHP
  * OpenSSL PHP Extension
  * PDO PHP Extension
  * Mbstring PHP Extension
  * Tokenizer PHP Extension
  * XML PHP Extension
  * Ctype PHP Extension
  * JSON PHP Extension
  * BCMath PHP Extension
* **Database:** MySQL 5.7.x or MariaDB 10.2.x
* **Web server:** Apache 2.4.x or NGINX 1.x or later \(preferred\)
* **Container:** Docker runtime
* **Data structure store:** Single-node Redis 5.0.3
* **Queue Management Service:** Laravel Horizon

## Related Topics

{% page-ref page="installation-guide.md" %}
