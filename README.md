### 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

``` 
CREATE TABLE employee (
    id SERIAL PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    birthday DATE,
    email VARCHAR(100) NOT NULL 
    );

``` 

### 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

``` 
insert into employee (name, birthday, email) values ('Kaine', '2021-12-14', 'kjanuary0@biblegateway.com');
insert into employee (name, birthday, email) values ('Massimo', '2022-05-14', 'mkiljan1@discuz.net');
insert into employee (name, birthday, email) values ('Remington', '2022-04-20', 'ritzkovsky2@wordpress.org');
insert into employee (name, birthday, email) values ('Cristal', '2021-12-09', 'cgumb3@jalbum.net');
insert into employee (name, birthday, email) values ('Abeu', '2022-06-11', 'ajasper4@weebly.com');
insert into employee (name, birthday, email) values ('Yoshi', '2022-03-20', 'yeveral5@a8.net');
insert into employee (name, birthday, email) values ('Isaiah', '2022-05-13', 'ichalfant6@mlb.com');
insert into employee (name, birthday, email) values ('Elonore', '2022-05-07', 'evassar7@soup.io');
insert into employee (name, birthday, email) values ('Tyson', '2021-11-27', 'tbentzen8@drupal.org');
insert into employee (name, birthday, email) values ('Aileen', '2022-03-13', 'afairbanks9@ed.gov');
insert into employee (name, birthday, email) values ('Gibbie', '2021-11-25', 'gchatera@wikia.com');
insert into employee (name, birthday, email) values ('Arlee', '2021-09-27', 'akindleyb@gravatar.com');
insert into employee (name, birthday, email) values ('Berty', '2022-03-26', 'bpickancec@devhub.com');
insert into employee (name, birthday, email) values ('Teddy', '2022-05-30', 'tmecod@cam.ac.uk');
insert into employee (name, birthday, email) values ('Arleyne', '2021-11-15', 'aribae@fotki.com');
insert into employee (name, birthday, email) values ('Bart', null, 'bshevlanf@google.pl');
insert into employee (name, birthday, email) values ('Karol', '2021-12-15', 'ksimnelg@apache.org');
insert into employee (name, birthday, email) values ('Jeane', '2022-05-30', 'jrickersyh@google.com.au');
insert into employee (name, birthday, email) values ('Sela', '2022-06-17', 'skimei@mozilla.com');
insert into employee (name, birthday, email) values ('Olympia', '2021-09-14', 'ozecchij@princeton.edu');
insert into employee (name, birthday, email) values ('Abran', '2022-02-06', 'alaethamk@mapquest.com');
insert into employee (name, birthday, email) values ('Margalo', '2021-12-30', 'mbynertl@google.ru');
insert into employee (name, birthday, email) values ('Cherianne', null, 'cgushm@desdev.cn');
insert into employee (name, birthday, email) values ('Estrella', '2021-08-14', 'ebristern@google.cn');
insert into employee (name, birthday, email) values ('Cayla', '2022-04-14', 'cmacgowno@businesswire.com');
insert into employee (name, birthday, email) values ('Simon', '2021-11-14', 'sbowellp@wikia.com');
insert into employee (name, birthday, email) values ('Deny', '2021-11-18', 'droomeq@amazon.com');
insert into employee (name, birthday, email) values ('Stearn', '2021-10-15', 'snewlandsr@washington.edu');
insert into employee (name, birthday, email) values ('Werner', null, 'wrawsthorns@deliciousdays.com');
insert into employee (name, birthday, email) values ('Barron', '2022-07-19', 'bescottt@columbia.edu');
insert into employee (name, birthday, email) values ('Laurena', '2022-02-12', 'ldadyu@bravesites.com');
insert into employee (name, birthday, email) values ('Morey', '2021-12-23', 'mnutleyv@uol.com.br');
insert into employee (name, birthday, email) values ('Hazel', '2022-02-06', 'hdecruzew@sitemeter.com');
insert into employee (name, birthday, email) values ('Christina', '2022-05-18', 'cginglesx@slideshare.net');
insert into employee (name, birthday, email) values ('Emerson', '2021-09-09', 'edimocky@gov.uk');
insert into employee (name, birthday, email) values ('Devlin', '2022-05-11', 'dgrenvillez@comcast.net');
insert into employee (name, birthday, email) values ('Lilias', '2022-02-01', 'lstrutz10@chicagotribune.com');
insert into employee (name, birthday, email) values ('Coleman', '2022-04-24', 'cquillinane11@bing.com');
insert into employee (name, birthday, email) values ('Andros', '2022-05-05', 'agrestie12@webs.com');
insert into employee (name, birthday, email) values ('Jillana', '2022-01-23', 'jprimak13@vistaprint.com');
insert into employee (name, birthday, email) values ('Austen', '2022-06-09', 'aitter14@github.com');
insert into employee (name, birthday, email) values ('Jefferey', '2022-06-23', 'jtroyes15@baidu.com');
insert into employee (name, birthday, email) values ('Carree', '2022-01-05', 'cdyte16@themeforest.net');
insert into employee (name, birthday, email) values ('Katusha', '2021-08-18', 'kholtum17@zimbio.com');
insert into employee (name, birthday, email) values ('Peria', '2021-11-23', 'ppock18@webmd.com');
insert into employee (name, birthday, email) values ('Winny', '2022-03-15', 'wkeene19@yale.edu');
insert into employee (name, birthday, email) values ('Emmott', null, 'ebrimblecombe1a@barnesandnoble.com');
insert into employee (name, birthday, email) values ('Caesar', '2022-04-14', 'cleavey1b@google.com');
insert into employee (name, birthday, email) values ('Nicko', null, 'nbuckle1c@hc360.com');
insert into employee (name, birthday, email) values ('Nicole', '2022-03-14', 'ngoscomb1d@edublogs.org');
``` 

### 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.


``` 
UPDATE SET name ='seyma', birthday='1999-08-12' WHERE id=15;
UPDATE SET email ='seyma@korak.com'  WHERE id=20 ;
UPDATE SET birthday ='1997-02-17'  WHERE id=3;
UPDATE SET name ='melike', email='melike@korak.com' WHERE id=41;
UPDATE SET name = 'ayaz' WHERE id=33;


``` 

### 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.


``` 
DELETE FROM employee WHERE id=41;
DELETE FROM employee WHERE name= 'seyma';
DELETE FROM employee WHERE id > 45;
DELETE FROM employee WHERE name LIKE '%n;
DELETE FROM employee WHERE birthday LIKE '1996%'; 


``` 



# SQL-Odev8