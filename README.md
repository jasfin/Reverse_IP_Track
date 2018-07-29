# Reverse_IP_Track
A simple php code to track the IP of users that visit a webpage

CREATE TABLE `database_name`.`table_name` ( `id` INT NOT NULL AUTO_INCREMENT , `time` TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP , `ip_address` VARCHAR(50) NOT NULL , `hostname` VARCHAR(100) NOT NULL , `cur_url` TEXT NOT NULL , `pre_url` TEXT NOT NULL , `xff_headers` TEXT NOT NULL , PRIMARY KEY (`id`)) ENGINE = InnoDB CHARSET=utf8 COLLATE utf8_general_ci;
