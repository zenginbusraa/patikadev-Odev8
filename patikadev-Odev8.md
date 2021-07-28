1. soru : test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

    `` CREATE TABLE employee (
    id INTEGER PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    birthday DATE,
     email VARCHAR(100)
    ); ``

2. soru : Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

`` insert into employee (id, name, birthday, email) values (1, 'Samantha', '1993/05/14', 'sbowld0@ning.com'); ``
`` insert into employee (id, name, birthday, email) values (2, 'Isabelita', '2015/10/19', 'iwixey1@ft.com');``
``insert into employee (id, name, birthday, email) values (3, 'Jere', '1901/09/20', 'jleat2@reference.com');``
``insert into employee (id, name, birthday, email) values (4, 'Jedidiah', '1972/05/26', 'jcrimin3@furl.net');``
``insert into employee (id, name, birthday, email) values (5, 'Wes', '1951/09/17', 'whastilow4@tiny.cc');``
``insert into employee (id, name, birthday, email) values (6, 'Marylinda', '1943/10/11', 'mpedri5@sina.com.cn');``
``insert into employee (id, name, birthday, email) values (7, 'Alyson', '1987/03/19', 'amattessen6@chicagotribune.com');``
``insert into employee (id, name, birthday, email) values (8, 'Celesta', '1910/08/30', 'cbaudrey7@cdbaby.com');``
``insert into employee (id, name, birthday, email) values (9, 'Loralyn', '1910/06/15', 'lbarwise8@home.pl');``
``insert into employee (id, name, birthday, email) values (10, 'Imelda', '1946/04/04', 'inisbet9@sphinn.com');``
``insert into employee (id, name, birthday, email) values (11, 'Evyn', '1964/01/25', 'esawfordea@vimeo.com');``
``insert into employee (id, name, birthday, email) values (12, 'Monika', '2001/04/02', 'mambrogiottib@va.gov');``
``insert into employee (id, name, birthday, email) values (13, 'Vassily', '1930/02/27', 'vdaughtonc@sourceforge.net');``
``insert into employee (id, name, birthday, email) values (14, 'Mick', '1990/12/30', 'mcluerd@thetimes.co.uk');``
``insert into employee (id, name, birthday, email) values (15, 'Tomi', '1929/02/01', 'tjellingse@mit.edu');``
``insert into employee (id, name, birthday, email) values (16, 'Gabriello', '1920/10/21', 'gjammetf@hp.com');``
``insert into employee (id, name, birthday, email) values (17, 'Tobin', '1995/08/31', 'tthomg@ucoz.ru');``
``insert into employee (id, name, birthday, email) values (18, 'Lenard', '1985/11/06', 'lwhitehairh@wp.com');``
``insert into employee (id, name, birthday, email) values (19, 'Shannan', '1953/01/13', 'sgreevesoni@amazonaws.com');``
``insert into employee (id, name, birthday, email) values (20, 'Eduard', '2014/01/21', 'edienesj@techcrunch.com');``
``insert into employee (id, name, birthday, email) values (21, 'Norby', '1974/02/16', 'nfarahark@parallels.com');``
``insert into employee (id, name, birthday, email) values (22, 'Celle', '1999/05/18', 'cmanwaringl@miibeian.gov.cn');``
``insert into employee (id, name, birthday, email) values (23, 'Germana', '1963/02/17', 'gpurdomm@unc.edu');``
``insert into employee (id, name, birthday, email) values (24, 'Erastus', '1943/07/30', 'ewilshawn@statcounter.com');``
``insert into employee (id, name, birthday, email) values (25, 'Ax', '2001/02/17', 'adysharto@nbcnews.com');``
``insert into employee (id, name, birthday, email) values (26, 'Khalil', '1993/06/15', 'kguinnp@google.de');``
``insert into employee (id, name, birthday, email) values (27, 'Marianna', '1980/12/31', 'mbednallq@zdnet.com');``
``insert into employee (id, name, birthday, email) values (28, 'Roderick', '1996/09/06', 'rrolfinir@va.gov');``
``insert into employee (id, name, birthday, email) values (29, 'Sigismund', '1997/02/16', 'sratkes@mail.ru');``
``insert into employee (id, name, birthday, email) values (30, 'Jeremias', '1961/03/05', 'jlinsteadt@i2i.jp');``
``insert into employee (id, name, birthday, email) values (31, 'Emmery', '1989/11/14', 'espadau@ebay.co.uk');``
``insert into employee (id, name, birthday, email) values (32, 'Keane', '1916/01/04', 'kpiersonv@xinhuanet.com');``
``insert into employee (id, name, birthday, email) values (33, 'Veronike', '1964/06/22', 'vharborw@opera.com');``
``insert into employee (id, name, birthday, email) values (34, 'Ulises', '2011/11/15', 'umclayx@google.ca');``
``insert into employee (id, name, birthday, email) values (35, 'Pennie', '1912/03/09', 'pbraziery@howstuffworks.com');``
``insert into employee (id, name, birthday, email) values (36, 'Alastair', '2001/08/03', 'afewz@twitpic.com');``
``insert into employee (id, name, birthday, email) values (37, 'Lewiss', '2016/02/21', 'lfontel10@mail.ru');``
``insert into employee (id, name, birthday, email) values (38, 'Sargent', '1922/05/08', 'srumsey11@mapquest.com');``
``insert into employee (id, name, birthday, email) values (39, 'Delano', '1919/09/27', 'dweekly12@theglobeandmail.com');``
``insert into employee (id, name, birthday, email) values (40, 'Giselbert', '1970/03/24', 'gwalklett13@google.es');``
``insert into employee (id, name, birthday, email) values (41, 'Chrystel', '1946/09/22', 'cbrinkley14@phoca.cz');``
``insert into employee (id, name, birthday, email) values (42, 'Jillian', '2016/07/10', 'jiggalden15@linkedin.com');``
``insert into employee (id, name, birthday, email) values (43, 'Genovera', '1961/12/11', 'gbanville16@friendfeed.com');``
``insert into employee (id, name, birthday, email) values (44, 'Lotta', '1957/06/08', 'libotson17@google.de');``
``insert into employee (id, name, birthday, email) values (45, 'Cal', '1985/09/04', 'cyeeles18@indiatimes.com');``
``insert into employee (id, name, birthday, email) values (46, 'Jacynth', '1930/08/26', 'jgayter19@sourceforge.net');``
``insert into employee (id, name, birthday, email) values (47, 'Francesca', '1971/02/09', 'feake1a@prlog.org');``
``insert into employee (id, name, birthday, email) values (48, 'Peadar', '1917/09/23', 'pscuse1b@imgur.com');``
``insert into employee (id, name, birthday, email) values (49, 'Der', '1988/02/20', 'dduchart1c@umn.edu');``
``insert into employee (id, name, birthday, email) values (50, 'Peggy', '2018/06/17', 'ploft1d@behance.net');``
``insert into employee (id, name, birthday, email) values (51, 'Rustie', '2018/04/19', 'rrheaume1e@netlog.com');``
``insert into employee (id, name, birthday, email) values (52, 'Stephannie', '1992/07/06', 'sbrookz1f@naver.com');``
``insert into employee (id, name, birthday, email) values (53, 'Glenn', '1977/08/22', 'ggreggersen1g@japanpost.jp');``
``insert into employee (id, name, birthday, email) values (54, 'Melva', '1997/08/28', 'mportchmouth1h@printfriendly.com');``
``insert into employee (id, name, birthday, email) values (55, 'Tyrone', '1983/05/20', 'tfaherty1i@wix.com');``
``insert into employee (id, name, birthday, email) values (56, 'Sterling', '1997/12/06', 'seteen1j@va.gov');``
``insert into employee (id, name, birthday, email) values (57, 'Fae', '1907/02/07', 'flumsden1k@4shared.com');``
``insert into employee (id, name, birthday, email) values (58, 'Lucille', '1962/03/30', 'lhallows1l@livejournal.com');``
``insert into employee (id, name, birthday, email) values (59, 'Maison', '1911/11/17', 'mplews1m@techcrunch.com');``
``insert into employee (id, name, birthday, email) values (60, 'Joelynn', '1939/03/03', 'jscrivin1n@baidu.com');``
``insert into employee (id, name, birthday, email) values (61, 'Roselin', '1913/12/28', 'rbarwack1o@surveymonkey.com');``
``insert into employee (id, name, birthday, email) values (62, 'Mitchael', '1995/05/06', 'mharnwell1p@shutterfly.com');``
``insert into employee (id, name, birthday, email) values (63, 'Albert', '1985/02/08', 'apeaple1q@salon.com');``
``insert into employee (id, name, birthday, email) values (64, 'Robin', '1984/09/23', 'rbickerdyke1r@t.co');``
``insert into employee (id, name, birthday, email) values (65, 'Hunter', '1917/05/27', 'hmyatt1s@redcross.org');``
``insert into employee (id, name, birthday, email) values (66, 'Dyna', '1967/09/03', 'dpape1t@marketwatch.com');``
``insert into employee (id, name, birthday, email) values (67, 'Bernadine', '2013/07/30', 'bcrowdace1u@japanpost.jp');``
``insert into employee (id, name, birthday, email) values (68, 'Eartha', '2020/12/07', 'eansill1v@multiply.com');``
``insert into employee (id, name, birthday, email) values (69, 'Thibaut', '1941/04/13', 'tmeasey1w@mapy.cz');``
``insert into employee (id, name, birthday, email) values (70, 'Glory', '1968/12/21', 'gtreweek1x@washingtonpost.com');``
``insert into employee (id, name, birthday, email) values (71, 'Timothy', '1917/11/22', 'tbainton1y@adobe.com');``
``insert into employee (id, name, birthday, email) values (72, 'Filmore', '1942/01/24', 'fbenzie1z@friendfeed.com');``
``insert into employee (id, name, birthday, email) values (73, 'Daniella', '1905/12/24', 'dantoinet20@blinklist.com');``
``insert into employee (id, name, birthday, email) values (74, 'Garvy', '2019/09/26', 'glassen21@fotki.com');``
``insert into employee (id, name, birthday, email) values (75, 'Barth', '1979/02/12', 'bhakewell22@phoca.cz');``
``insert into employee (id, name, birthday, email) values (76, 'Tomaso', '2000/03/05', 'tmccaffrey23@typepad.com');``
``insert into employee (id, name, birthday, email) values (77, 'Rica', '1986/01/18', 'rhare24@hostgator.com');``
``insert into employee (id, name, birthday, email) values (78, 'Mort', '1931/12/12', 'mlomaz25@icio.us');``
``insert into employee (id, name, birthday, email) values (79, 'Martyn', '1979/03/22', 'moller26@pen.io');``
``insert into employee (id, name, birthday, email) values (80, 'Smith', '1945/09/05', 'ssleney27@macromedia.com');``
``insert into employee (id, name, birthday, email) values (81, 'Greggory', '1938/04/19', 'gtommaseo28@list-manage.com');``
``insert into employee (id, name, birthday, email) values (82, 'Germaine', '1965/06/07', 'gsikorski29@who.int');``
``insert into employee (id, name, birthday, email) values (83, 'Ansell', '2003/02/22', 'adrayn2a@weather.com');``
``insert into employee (id, name, birthday, email) values (84, 'Brita', '1949/11/15', 'bjager2b@yolasite.com');``
``insert into employee (id, name, birthday, email) values (85, 'Stepha', '1927/02/16', 'spreddy2c@yellowpages.com');``
``insert into employee (id, name, birthday, email) values (86, 'Humberto', '2004/06/11', 'hbrugger2d@ovh.net');``
``insert into employee (id, name, birthday, email) values (87, 'Arron', '1986/11/16', 'ayeo2e@state.tx.us');``
``insert into employee (id, name, birthday, email) values (88, 'Shane', '1902/11/23', 'sboyles2f@who.int');``
``insert into employee (id, name, birthday, email) values (89, 'Anissa', '1923/02/12', 'afrend2g@noaa.gov');``
``insert into employee (id, name, birthday, email) values (90, 'Warner', '1986/02/05', 'wbagenal2h@mlb.com');``
``insert into employee (id, name, birthday, email) values (91, 'Padgett', '1978/12/18', 'ppizey2i@lycos.com');``
``insert into employee (id, name, birthday, email) values (92, 'Wynn', '1906/11/19', 'wmenhenitt2j@addthis.com');``
``insert into employee (id, name, birthday, email) values (93, 'Adham', '2001/09/17', 'ascammell2k@zimbio.com');``
``insert into employee (id, name, birthday, email) values (94, 'Palm', '1977/05/14', 'pbardwell2l@adobe.com');``
``insert into employee (id, name, birthday, email) values (95, 'Pip', '1984/10/28', 'pbenzing2m@independent.co.uk');``
``insert into employee (id, name, birthday, email) values (96, 'Barbie', '1901/07/06', 'bgyford2n@google.co.jp');``
``insert into employee (id, name, birthday, email) values (97, 'Torey', '1937/07/21', 'tbeggs2o@woothemes.com');``
``insert into employee (id, name, birthday, email) values (98, 'Darrel', '1915/03/18', 'dcota2p@dell.com');``
``insert into employee (id, name, birthday, email) values (99, 'Eugenio', '2003/02/07', 'ecoathup2q@google.de');``
``insert into employee (id, name, birthday, email) values (100, 'Lonni', '1974/12/12', 'lpaten2r@histats.com'); ``


3. soru : Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

    `` UPDATE employee
        SET name = 'Ali',
	        birthday = '1999-01-02',
	        email = 'ali@hotmail.com'
        WHERE id < 5; ``

    `` UPDATE employee
            SET name = 'Derya',
	            birthday = '1909-11-02',
	            email = 'derya@dell.com'
            WHERE name LIKE 'A%'; ``

    `` UPDATE employee
            SET name = 'Peader Pay',
	            birthday = '1909-11-02',
	            email = 'pey@akl.com'
            WHERE name = 'Peader'; ``

    `` UPDATE employee
            SET name = 'Merve',
	            birthday = '1909-11-02',
	            email = 'merve@akl.com'
            WHERE name LIKE '_a%' ; ``

    `` UPDATE employee
            SET name = 'Germana',
	            birthday = '1963-02-25',
	            email = 'germana@unc.edu'
            WHERE birthday = '1963-02-17' ; ``



4. soru : Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.


    `` DELETE FROM employee
    WHERE name = 'Merve';``

    ``DELETE FROM employee
    WHERE name LIKE  '%e_';``

    ``DELETE FROM employee
    WHERE email LIKE  '%@dell.com'; ``

    ``DELETE FROM employee
    WHERE birthday = '1909-11-02' ; ``

    ``DELETE FROM employee
    WHERE id BETWEEN 47 AND 51 ;``
