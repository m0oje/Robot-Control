# Robot-Control
A web page for controlling a robot that features 5 buttons: 4 for navigating and 1 for stop.
these images displays the page.

![254608774-64a03459-4e3e-417c-8d58-309a952de100](https://github.com/m0oje/Robot-Control/assets/138607426/64eba7c7-4b9c-4838-94d7-b5aeef8d118f)

![254609090-d894d85e-c7dd-4fa5-95fe-f4dc5a0040db](https://github.com/m0oje/Robot-Control/assets/138607426/d53fe798-bf45-4865-a791-f64a505a0105)

while this image shows an example of the database that has been connected to the webpage.

![254609481-570aa853-8cbf-42cc-9598-3936c98a8b3d](https://github.com/m0oje/Robot-Control/assets/138607426/58bd6540-b357-4c62-bfd9-abd2ac1786b3)

The SQL code required to build a table for storing the commands is as follows.

``` 
CREATE TABLE `commands` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `command` varchar(255) NOT NULL,
  `timestamp` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;
 ```

