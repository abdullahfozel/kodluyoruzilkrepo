Merhabalar,

* 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
 
CREATE TABLE employee (  
  id INTEGER,  
  name VARCHAR(50) NOT NULL,  
  email VARCHAR(100),  
  birthday DATE  
);

* 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.



* 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee  
SET name = 'Mayak'  
WHERE id = 2;  
  
* 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee  
WHERE name = 'Mayak';

Kolay Gelsin.
