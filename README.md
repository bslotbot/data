CREATE TABLE `admin_member` (
  `user` varchar(40) NOT NULL default '', 
  `password` varchar(40) NOT NULL default ''
) TYPE = MyISAM;
INSERT INTO `admin_member` 
VALUES 
  ('admin', 'admin');
CREATE TABLE `mail` (
  `subject` varchar(120) NOT NULL default '', 
  `form_mail` longtext NOT NULL
) TYPE = MyISAM;
CREATE TABLE `member` (
  `id` int(6) NOT NULL auto_increment, 
  `member_id` varchar(20) NOT NULL default '', 
  `name` varchar(50) NOT NULL default '', 
  `date` int(2) NOT NULL default '0', 
  `month` int(2) NOT NULL default '0', 
  `year` varchar(4) NOT NULL default '', 
  `age` varchar(10) NOT NULL default '', 
  `sex` varchar(8) NOT NULL default '', 
  `address` varchar(150) NOT NULL default '', 
  `amper` varchar(40) NOT NULL default '', 
  `province` varchar(40) NOT NULL default '', 
  `zipcode` varchar(15) NOT NULL default '', 
  `phone` varchar(10) NOT NULL default '', 
  `education` varchar(30) NOT NULL default '', 
  `work` varchar(30) NOT NULL default '', 
  `user` varchar(30) NOT NULL default '', 
  `password` varchar(30) NOT NULL default '', 
  `email` varchar(40) NOT NULL default '', 
  `signup` varchar(40) NOT NULL default '', 
  PRIMARY KEY (`id`)
) TYPE = MyISAM AUTO_INCREMENT = 2;
