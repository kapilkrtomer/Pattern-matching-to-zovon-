Pattern-matching-to-zovon-
==========================

#!/usr/bin/python


line1 ="""Kids+Gifts+Gifts For Kids+Gifts For Kids
Kids+Gifts+Other Home Accessory+Other Home Accessory
Kids+Gifts+Other Home Accessory+Other Home Accessory
Kids+Jewellery+Gifts For Girlfriend+Gifts For Girlfriend
Kids+Jewellery+Gifts For Her+Gifts For Her
Kids+Sarees+Other Actress Sarees+Other Actress Sarees
Kids+Sarees+Other Sarees+Other Sarees
Men+Gifts+Gifts For Brother+Gifts For Brother
Men+Gifts+Gifts For Him+Gifts For Him
Men+Rakhinew+Gifts For Husband+Gifts For Husband
Men+Sarees+Shimmer Sarees+Shimmer Sarees
women+Gifts+Anniversary Gifts+Anniversary Gifts
women+Gifts+Birthday Gifts+Birthday Gifts
women+Gifts+Christmas Decor+Christmas Decor
women+Gifts+Christmas Gifts+Christmas Gifts
women+Gifts+Deepavali Aarti Thali Diwali Pooja Thalis+Deepavali Aarti Thali Diwali Pooja Thalis
women+Gifts+Diwali Corporate Gifts+Diwali Corporate Gifts
women+Gifts+Diwali Decorations+Diwali Decorations
women+Gifts+Diwali Puja Thalis+Diwali Puja Thalis
women+Gifts+Diwali Silver Gifts+Diwali Silver Gifts
women+Gifts+Eid Collection+Eid Collection
women+Gifts+Eid Gift+Eid Gift
women+Gifts+Eid Sarees Dresses+Eid Sarees Dresses
women+Gifts+Engagement Gifts+Engagement Gifts
women+Gifts+Ganesh Chaturthi Gifts+Ganesh Chaturthi Gifts
women+Gifts+Gifts For Mom+Gifts For Mom
women+Gifts+Housewarming Gifts+Housewarming Gifts
women+Gifts+Office Opening Gifts+Office Opening Gifts
women+Gifts+Onam Festival Gifts Kerala 2013+Onam Festival Gifts Kerala 2013
women+Gifts+Phone Cases+Phone Cases
women+Gifts+Ramadan Gifts+Ramadan Gifts
women+Gifts+Sculptures+Sculptures
women+Gifts+Thanksgiving Gifts+Thanksgiving Gifts
women+Gifts+Valentine Gifts+Valentine Gifts
women+Gifts+Wedding Gifts+Wedding Gifts
women+Jewellery+Anklets+Anklets
women+Jewellery+Bajuband+Bajuband
women+Jewellery+Bangles And Bracelets+Bangles And Bracelets
women+Jewellery+Bangles And Bracelets+Bangles And Bracelets
women+Jewellery+Bracelets+Bracelets
women+Jewellery+Bridal Sets+Bridal Sets
women+Jewellery+Brooch+Brooch
women+Jewellery+Danglers Drops+Danglers Drops
women+Jewellery+Earrings+Earrings
women+Jewellery+Gifts For Sister+Gifts For Sister
women+Jewellery+Gifts For Wife+Gifts For Wife
women+Jewellery+Hair Pins+Hair Pins
women+Jewellery+Hoops+Hoops
women+Jewellery+Jhumkas+Jhumkas
women+Jewellery+Maang Tikka+Maang Tikka
women+Jewellery+Mangalsutra+Mangalsutra
women+Jewellery+Necklace Sets+Necklace Sets
women+Jewellery+Necklaces+Necklaces
women+Jewellery+Nose Ring+Nose Ring
women+Jewellery+Pendants+Pendants
women+Jewellery+Rings+Rings
women+Jewellery+Studs+Studs
women+Jewellery+Watches+Watches
women+Lehengas+Anushka Sharma Saree+Anushka Sharma Saree
women+Lehengas+Bollywood Lehengas+Bollywood Lehengas
women+Lehengas+Bridal Lehengas+Bridal Lehengas
women+Lehengas+Dresses+Dresses
women+Lehengas+Ghagra Choli+Ghagra Choli
women+Lehengas+Lehenga Choli+Lehenga Choli
women+Lehengas+Lehenga Sarees+Lehenga Sarees
women+Lehengas+Lehenga Sarees+Lehenga Sarees
women+Lehengas+Lehengas+Lehengas
women+Lehengas+Party Wear Sarees+Party Wear Sarees
women+Lehengas+Priyanka Chopra Saree+Priyanka Chopra Saree
women+Lehengas+Shilpa Shetty Sarees+Shilpa Shetty Sarees
women+Lehengas+Sonam Kapoor Saree+Sonam Kapoor Saree
women+More+Anarkali Salwar Kameez+Anarkali Salwar Kameez
women+More+Bollywood Salwar Kameez Online+Bollywood Salwar Kameez Online
women+More+Cotton Salwar Kameez+Cotton Salwar Kameez
women+More+Dress Materials+Dress Materials
women+More+Eid Special Salwar Kameez+Eid Special Salwar Kameez
women+More+Kurtas And Kurtis+Kurtas And Kurtis
women+More+Leggings+Leggings
women+More+Pakistani Salwar Kameez+Pakistani Salwar Kameez
women+More+Party Wear Salwar Kameez+Party Wear Salwar Kameez
women+More+Patiala Salwar+Patiala Salwar
women+More+Pyjamas+Pyjamas
women+More+Readymade Suits+Readymade Suits
women+More+Salwar Kameez+Salwar Kameez
women+More+Salwars And Churidars+Salwars And Churidars
women+More+Semi Stitched Salwar Suits+Semi Stitched Salwar Suits
women+More+Shorts+Shorts
women+More+Skirts+Skirts
women+More+Stole And Dupattas+Stole And Dupattas
women+More+Tops+Tops
women+More+Tunics+Tunics
women+More+Wedding Salwar Kameez+Wedding Salwar Kameez
women+Sarees+Aishwarya Rai Saree+Aishwarya Rai Saree
women+Sarees+Art Silk Sarees+Art Silk Sarees
women+Sarees+Banarasi Sarees+Banarasi Sarees
women+Sarees+Banarasi Silk Sarees+Banarasi Silk Sarees
women+Sarees+Bandhani Sarees Bandhej+Bandhani Sarees Bandhej
women+Sarees+Bhagalpuri Silk Sarees+Bhagalpuri Silk Sarees
women+Sarees+Bipasha Basu Sarees+Bipasha Basu Sarees
women+Sarees+Blouse+Blouse
women+Sarees+Bollywood Sarees+Bollywood Sarees
women+Sarees+Brasso Sarees+Brasso Sarees
women+Sarees+Bridal Sarees+Bridal Sarees
women+Sarees+Brocade Sarees+Brocade Sarees
women+Sarees+Chanderi Sarees+Chanderi Sarees
women+Sarees+Chiffon Sarees+Chiffon Sarees
women+Sarees+Chikankari Saris+Chikankari Saris
women+Sarees+Cotton Sarees+Cotton Sarees
women+Sarees+Cotton Silk Sarees+Cotton Silk Sarees
women+Sarees+Crepe Sarees+Crepe Sarees
women+Sarees+Deepika Padukone Saree+Deepika Padukone Saree
women+Sarees+Designer Embroidered Sarees+Designer Embroidered Sarees
women+Sarees+Dupion Sarees+Dupion Sarees
women+Sarees+Faux Sarees+Faux Sarees
women+Sarees+Georgette Sarees+Georgette Sarees
women+Sarees+Half Sarees+Half Sarees
women+Sarees+Hand Woven Sarees+Hand Woven Sarees
women+Sarees+Heavy Work Sarees+Heavy Work Sarees
women+Sarees+Ikat Sarees+Ikat Sarees
women+Sarees+Jacquard Sarees+Jacquard Sarees
women+Sarees+Jute Sarees+Jute Sarees
women+Sarees+Kalamkari Sarees+Kalamkari Sarees
women+Sarees+Kanchipuram Silk Sarees+Kanchipuram Silk Sarees
women+Sarees+Kareena Kapoor Sarees+Kareena Kapoor Sarees
women+Sarees+Katrina Kaif Saree+Katrina Kaif Saree
women+Sarees+Kerala Sarees+Kerala Sarees
women+Sarees+Kota Silk Sarees+Kota Silk Sarees
women+Sarees+Madhuri Dixit Sarees+Madhuri Dixit Sarees
women+Sarees+Net Sarees+Net Sarees
women+Sarees+One Minute Sarees+One Minute Sarees
women+Sarees+Organza Sarees+Organza Sarees
women+Sarees+Patola Saris+Patola Saris
women+Sarees+Printed Sarees+Printed Sarees
women+Sarees+Sarees+Sarees
women+Sarees+Satin Sarees+Satin Sarees
women+Sarees+Silk Sarees+Silk Sarees
women+Sarees+Sonakshi Sinha Saree+Sonakshi Sinha Saree
women+Sarees+Sridevi Sarees+Sridevi Sarees
women+Sarees+Supernet Sarees+Supernet Sarees
women+Sarees+Tissue Sarees+Tissue Sarees
women+Sarees+Traditional Sarees+Traditional Sarees
women+Sarees+Tussar Silk Sarees+Tussar Silk Sarees
women+Sarees+Velvet Sarees+Velvet Sarees
women+Sarees+Vidya Balan Saree+Vidya Balan Saree
women+Sarees+Viscose Sarees+Viscose Sarees
women+Sarees+Wedding Sarees+Wedding Sarees"""


line2 = """Gifts+Kids+General gifts
Gifts+men+house warming gifts
Gifts+women+house warming gifts
Gifts+women+general gifts
Gifts+women+general gifts
Women+clothing+Sarees
Women+clothing+Sarees
Gifts+men+general gifts
Gifts+men+general gifts
Gifts+men+general gifts
Women+clothing+Sarees
Gifts+women+anniversary-gifts
Gifts+women+Birthday Gifts
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+general gifts
Gifts+women+house-warming-gifts
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+general gifts
Gifts+women+Gifts for Occasion
Gifts+women+house-warming-gifts
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
Gifts+women+Gifts for Occasion
women+jewellery+anklets
women+jewellery+armlets
women+jewellery+Bangles
women+jewellery+ bracelets
women+jewellery+bracelets
women+jewellery+necklace-sets
women+jewellery+pins-&-brooches
women+jewellery+Earrings
women+jewellery+Earrings
Gifts+women+general gifts
Gifts+women+general gifts
women+jwellery+Hair Pins
women+ jewellery+ earrings
women+ jewellery+ earrings
women+ jewellery+ head-gears
women+ jewellery+ necklace-sets
women+ jewellery+ necklace-sets
women+ jewellery+ necklaces
women+ jewellery+ Nose & ear-studs
women+ jewellery+ pendant-sets
women+ jewellery+ rings
women+ jewellery+ Nose & ear-studs
women+ jewellery+ watches
Women+clothing+Sarees
Women+clothing+lehengas
Women+clothing+lehengas
Women+clothing+dresses
Women+clothing+lehengas
Women+clothing+lehengas
Women+clothing+Sarees
Women+clothing+lehengas
Women+clothing+lehengas
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+Kurtis & Kurtsas
Women+clothing+leggings
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ indian-suits
Women+clothing+ short-skirts
Women+clothing+ short-skirts
Women+clothing+ accessories
Women+clothing+  tops-&-tees
Women+clothing+  tops-&-tees
Women+clothing+ indian-suits
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees
Women+clothing+Sarees"""

import MySQLdb
import sys
from bs4 import BeautifulSoup
from lxml import html 



class to_zovon(object):
    def __init__(self, dbname, tablename, sitename):
        self.line1 = line1
        self.line2 = line2
	self.dbname = dbname
	self.tablename = tablename
        self.sitename = sitename



    def __del__(self):
        self.db.close()
        self.db2.close()



    def to_dict(self):
        key_list = self.line1.split("\n")
        val_list = self.line2.replace("-", "").split("\n")
        self.key_val_dict = dict(zip(key_list, val_list))

    def database_connect(self):
        self.db = db = MySQLdb.connect("localhost","root","6Tresxcvbhy", self.dbname)
        self.cursor = cursor = db.cursor()

        self.db2 = db2 = MySQLdb.connect("54.201.218.138","root","india@123", "zov")
	self.cursor2 = cursor2 = db2.cursor()

    def update_fetch_row(self):
        db = self.db
	cursor = self.cursor
        
        #sql = """UPDATE %s set upload_status = 'NO' """ %(self.tablename)
        #cursor.execute(sql)
        #db.commit()

        sql = "SELECT * FROM %s where upload_status = 'NO' AND status = 'A' " %(self.tablename)
	cursor.execute(sql)


    def fetch_row_mydb(self):
        my_strip = self.my_strip
	key_val_dict = self.key_val_dict
	ptrn_mtch = self.ptrn_mtch
        sitename = self.sitename
        cursor = self.cursor

        results = cursor.fetchall()
        #results = [cursor.fetchone()]
	for row in results[:2]:
	   row =  map(my_strip, row)
           try:
               row[19] = BeautifulSoup(row[19], "html.parser").get_text()
           except:
               pass
          
           try:
               row[20] = BeautifulSoup(row[20], "html.parser").get_text()
           except:
               pass
           
           ptrn_mtch(row, key_val_dict, sitename)



    def ptrn_mtch(self, row, key_val_dict, sitename):
        target = row[13]
	category = row[5]
	sub_category = row[6]
	ss_category = row[7]

        try:
            my_key = "%s+%s+%s+%s" %(target, category, sub_category, ss_category)
	    his_val = key_val_dict[my_key]

            his_val_list = tuple(his_val.split("+"))

	    self.his_val_list = his_val_list
	    self.insert_into_zov(row, sitename)

        except:
            pass



    def insert_into_zov(self, rows, sitename):

        his_val_list = self.his_val_list
        
        if len(his_val_list) == 3:
            zov_target, zov_category, zov_sub_category = his_val_list
	    zov_ss_category = ''
   
        elif len(his_val_list) == 2:
            zov_target, zov_category = his_val_list
	    zov_sub_category = zov_ss_category = ''

	elif len(his_val_list) == 4:
	    zov_target, zov_category, zov_sub_category, ss_category = his_val_list

	else:
	    zov_target = his_val_list[0]
	    zov_category, zov_sub_category, ss_category = ''

        sql = """INSERT INTO zovondetails_b( SKU, Title, Link, Price, Category, subCategory, Brand, Image, ListPrice,\
                                             ColourName, targetAudience, productUrl, seller, metaTitle, metaDescription,\
                                             size, log_discription, log_specification, seller_brand) \
                                     VALUES( "%s", "%s", "%s", "%s", "%s", "%s", "%s", "%s", "%s", "%s", "%s", "%s", \
                                             "%s", "%s", "%s", "%s", "%s", "%s", "%s")"""

        start = rows[4].find(".")

        if start != -1:
            rows[4] = "".join(rows[4].split(".")[-1].replace(",", "").split())

        else:
            rows[4] = "".join(rows[4].split()[-1].replace(",", "").split())


        start = rows[11].find(".")

        if start != -1:
            rows[11] = "".join(rows[11].split(".")[-1].replace(",", "").split())

        else:
            rows[11] = "".join(rows[11].split()[-1].replace(",", "").split())

        end = rows[10].rfind("?")
        start = rows[10].rfind("/")
        rows[10] = rows[10][start+1 : end ]

        

        info = (rows[1], rows[2], rows[14], rows[4], zov_category.lower(), zov_sub_category.lower(), rows[9], rows[10], 
                rows[11], rows[12], zov_target.lower(), rows[2], rows[15], rows[16], rows[17], rows[18], rows[19],
                rows[20], sitename)
 
        sql = sql %(info)

        try:
            self.cursor2.execute(sql)
            self.db2.commit()
            sql = """UPDATE %s set upload_status = 'YES' where task_id = %s""" %(self.tablename, int(rows[0]))
            self.cursor.execute(sql)
            self.db.commit()
            print "inserted................................................................................"

        except:
            sql = """UPDATE %s set upload_status = 'F' where task_id = %s""" %(self.tablename, int(rows[0]))
            self.cursor.execute(sql)
            self.db.commit()
            self.db2.rollback()
            print "failed..................................................................................."

        #print sql
        

	

    def my_strip(self, x):
        try:
            x = str(x).replace("\\", " ").replace("\'","").replace("\"", "").replace("\a", " ").replace("\b", " ").replace("\f", " ").replace("\r", " ").replace("\t", " ").replace("\v", " ").replace("\n", " ").strip()

        except:
            x = str(x.encode("ascii", "ignore")).replace("\\", " ").replace("\'","").replace("\"", "").replace("\a", " ").replace("\b", " ").replace("\f", " ").replace("\r", " ").replace("\t", " ").replace("\v", " ").replace("\n" , " ").strip()

        return x
   


def supermain():
    obj = to_zovon("zivame", "zivame_data", "www.zivame.com")
    obj.to_dict()
    obj.database_connect()
    obj.update_fetch_row()
    obj.fetch_row_mydb()



if __name__=="__main__": 
    supermain()
