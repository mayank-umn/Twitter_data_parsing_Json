```python
import json
with open('C:/Users/mayan/Desktop/1TouchSolutions/Twitterdata_features/businessDiscovery.json', encoding='utf-8') as f:
    x = json.loads(f.read())
    print(x)
```

    [{'business_discovery': {'biography': "Bharatiya Janata Party, founded in 1980, is World's largest political party. It currently leads the NDA, which is governing India.  #BJP  #India", 'followers_count': 3297381, 'follows_count': 0, 'id': '17841400193077467', 'ig_id': 1757894435, 'media_count': 3616, 'name': 'BJP - Bharatiya Janata Party', 'profile_picture_url': 'https://scontent.fdel1-1.fna.fbcdn.net/v/t51.2885-15/22858431_375803636191252_1114185658420690944_n.jpg?_nc_cat=1&_nc_sid=86c713&_nc_ohc=_8aTjRZ5dpkAX-dVRH1&_nc_ht=scontent.fdel1-1.fna&oh=70678535e7f38bc275480ff154a4e85b&oe=5F15917D', 'username': 'bjp4india', 'website': 'https://www.bjp.org/membership', 'media': {'data': [{'caption': 'लड़ाई जारी है लेकिन हौसले बुलंद है। जीतेंगे हम...', 'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/105281340_196641258291866_7205467741881983526_n.mp4?_nc_cat=100&vs=17869559734829517_3228560770&_nc_vs=HBksFQAYJEdEeDNSZ2FhUWxrYzJMSUFBQ1ppYVN1ODl2NWpia1lMQUFBRhUAAsgBABUAGCRHTWphT1FiZzRlMjRVdzREQU1CUFp5T05uVVVJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpq8%2BtOikb4%2FFQIoAkMzLBdAPirAgxJumBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=AW8hg-F_MkIAX_4qXXe&_nc_ht=video.fdel1-4.fna&oh=177c7874d52c3b0a600436b702aa01b1&oe=5F1767E5&_nc_rid=0b3942b744', 'media_type': 'VIDEO', 'like_count': 16018, 'comments_count': 66, 'timestamp': '2020-06-22T05:48:45+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBuegpTAQRn/', 'id': '17863465609926295'}, {'caption': 'BJP National President Shri jpnaddaofficial performs yoga at his residence on #InternationalYogaDay today. #MyLifeMyYoga', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104053466_2317964778511660_5981624510555492019_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=JUPXH3DmOxMAX8y1O3N&_nc_ht=scontent.cdninstagram.com&oh=0a19fa241fd1c3d68c7856f2ca2b2a75&oe=5F15DE50', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 63768, 'comments_count': 148, 'timestamp': '2020-06-21T04:02:50+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBrtnoggN_k/', 'id': '18059996809227284'}, {'caption': 'कोरोना के संकटकाल में भी टेक्नोलॉजी के माध्यम से देश के जन-जन तक पहुंच रही है भारतीय जनता पार्टी। आज भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial के राजस्थान जनसंवाद रैली में संबोधन को सुनते आमजन।', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105414284_265420581539185_4630206849005528189_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=Hxn-B9z-d0EAX_IB2AH&_nc_ht=scontent.cdninstagram.com&oh=e719ea92eab6f1b1961397dfb105502e&oe=5F157E9D', 'media_type': 'IMAGE', 'like_count': 34851, 'comments_count': 118, 'timestamp': '2020-06-20T13:37:31+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBqKlz4ASym/', 'id': '18091724080175849'}, {'caption': 'राहुल गांधी, सुनिए हमारे वीर जवान के वीर पिता की भावनाओं को और बंद कीजिए उनके नाम पर निकृष्ट राजनीति। #india #bjp #china', 'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104735923_1188447364835330_3114894258955085295_n.mp4?_nc_cat=100&vs=17877093337693291_566229461&_nc_vs=HBksFQAYJEdMTWtQZ1lDNkFQMzRqZ0VBTy1sNnpuVFV6b3Jia1lMQUFBRhUAAsgBABUAGCRHR0NaT1FhUWRuQ1BreVlCQU1XdXdwd1V0UmtJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFtaZosnkx8E%2FFQIoAkMzLBdAQEiTdLxqfxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=0REsp84tcW8AX9F6h3j&_nc_ht=video.fdel1-4.fna&oh=1159a1ac7de66f95cd74591ff9055f93&oe=5F1764F9&_nc_rid=7c1a08f482', 'media_type': 'VIDEO', 'like_count': 19614, 'comments_count': 179, 'timestamp': '2020-06-20T05:01:07+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBpPeZxAd5z/', 'id': '17887502845575049'}, {'caption': 'भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial 20 जून 2020 को दोपहर 12.30 बजे वीडियो कॉन्फ़्रेंसिंग के माध्यम से राजस्थान जनसंवाद रैली को संबोधित करेंगे। BJP4Rajasthan', 'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104265490_292049665296242_423465061768528093_n.mp4?_nc_cat=107&vs=17857036247024519_3284310992&_nc_vs=HBksFQAYJEdCTDNOZ1p5aDQ0Y25na0JBTjJBZ09VNmNfQUZia1lMQUFBRhUAAsgBABUAGCRHSDZYT0FZS0hFWklvLUVBQUc5Y3c3ZmJrMlpvYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFo7X66enuLg%2FFQIoAkMzLBdANV3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=saabCtPvwukAX83CWTS&_nc_ht=video.fdel1-2.fna&oh=4f35aada4816b6b365a2b0446cc5a66f&oe=5F15A1C1&_nc_rid=4ea34c4e61', 'media_type': 'VIDEO', 'like_count': 16005, 'comments_count': 44, 'timestamp': '2020-06-19T17:11:30+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBn-QQ9FWKa/', 'id': '18152066587031624'}, {'caption': 'PM narendramodi holds All Party Meeting to discuss situation in India-China border areas\n.\n.\n20 of our brave soldiers made the supreme sacrifice in Ladakh but also taught a lesson to those who dared to look towards our motherland. Neither is anyone inside our territory nor is any of our post captured; India wants peace and friendship, but upholding sovereignty is foremost: PM narendramodi', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104101998_579856346007751_1019788892395299541_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=tacps046vWcAX8u0QB2&_nc_ht=scontent.cdninstagram.com&oh=ec16af88a1bad743b7948aea877bc480&oe=5F17339C', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 88308, 'comments_count': 319, 'timestamp': '2020-06-19T16:36:37+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBn6Sz0gg-V/', 'id': '17888904943571172'}, {'caption': "Modi govt's huge relief to Delhiites. \nOn instructions of Home Minister Shri amitshahofficial, the cost of treatment of COVID-19 patients in private hospitals of Delhi has been reduced by about two-thirds.\n\nPPE kits and medicines are also included in the new rates.", 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105020102_191367085579754_6719776562378654198_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=cUJkZK9oWeUAX8bCrdX&_nc_ht=scontent.cdninstagram.com&oh=9c5485f63f3e7558279e69169bcc28b2&oe=5F16869C', 'media_type': 'IMAGE', 'like_count': 28970, 'comments_count': 269, 'timestamp': '2020-06-19T13:26:29+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBnkiO9gXcK/', 'id': '17875144507732012'}, {'caption': 'BJP has decided to postpone all its political programmes including virtual rallies for next 2 days.', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104103516_103667658011266_3962349400865496458_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=SrzDIB3ShaYAX9rdr23&_nc_ht=scontent.cdninstagram.com&oh=3370eb484c2794f990b23eb2f3b8b697&oe=5F1733FD', 'media_type': 'IMAGE', 'like_count': 23698, 'comments_count': 145, 'timestamp': '2020-06-18T06:09:47+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBkNw3AAJ0A/', 'id': '18121635580113888'}, {'caption': '1857 के प्रथम स्वतंत्रता संग्राम में अंग्रेज़ी शासन के विरुद्ध अग्रिम भूमिका निभाकर अपने प्राणों की आहुति देने वाली महान वीरांगना रानी लक्ष्मीबाई की पुण्यतिथि पर कोटि-कोटि नमन।', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103661980_566983254001582_7367512126551480632_n.jpg?_nc_cat=108&_nc_sid=8ae9d6&_nc_ohc=C5KmytflgHYAX-jQdzx&_nc_ht=scontent.cdninstagram.com&oh=cb83d40338ed9cd684123c8b47109659&oe=5F16ECD6', 'media_type': 'IMAGE', 'like_count': 37857, 'comments_count': 231, 'timestamp': '2020-06-18T04:33:14+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBkCtskA-wB/', 'id': '17874635890734764'}, {'caption': 'भारत शांति चाहता है, लेकिन भारत उकसाने पर हर हाल में यथोचित जवाब देने में सक्षम है। हमारे दिवंगत शहीद वीर जवानों के विषय में देश को इस बात में गर्व होगा कि वे मारते-मारते मरे हैं: प्रधानमंत्री श्री narendramodi', 'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104485235_2728637797458196_1083507323252640862_n.mp4?_nc_cat=102&vs=17876598496707417_2072603921&_nc_vs=HBksFQAYJEdITlJPZ1lVWWFOX3JyRUpBRjRNQW5vclpBa1Bia1lMQUFBRhUAAsgBABUAGCRHS2YwTmdZQ0lIVjRYQUVKQUFrWHVCYl85Ynd3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFrLqvqv9qsE%2FFQIoAkMzLBdARfeNT987ZBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=JTZii5Y9M0oAX-V7vRo&_nc_ht=video.fdel1-4.fna&oh=8183b16ee1a4786bb958993128c4bfdc&oe=5F15687B&_nc_rid=b66e01f968', 'media_type': 'VIDEO', 'like_count': 32520, 'comments_count': 454, 'timestamp': '2020-06-17T15:54:43+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBir3VWARag/', 'id': '18110380408137861'}, {'caption': "Stay tuned for BJP National President Shri jpnaddaofficial's 'Kerala Jan Samvad Rally' on 16 June 2020.\n\nWatch the live webcast of the virtual rally on all social media platforms of BJP. #BJPJanSamvad", 'media_url': 'https://video.fdel1-1.fna.fbcdn.net/v/t50.2886-16/103700248_282523916206191_4692889505717351644_n.mp4?_nc_cat=110&vs=17861586256940324_2588048645&_nc_vs=HBksFQAYJEdCaFhMZ1p2Z0tvNTlBQUJBTnowY0RZa2ZpQkJia1lMQUFBRhUAAsgBABUAGCRHQUxOSmdaYUF2SEZBdTRBQUtCOUE1MElmcFF0YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsjOgsyTwbo%2FFQIoAkMzLBdANTvnbItDlhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=66F1LprSIjUAX883oTc&_nc_ht=video.fdel1-1.fna&oh=db5c5e29bd5290dc448e599893fd27cd&oe=5F165617&_nc_rid=9e8615f55b', 'media_type': 'VIDEO', 'like_count': 14411, 'comments_count': 66, 'timestamp': '2020-06-15T15:43:51+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBdhBXRA31s/', 'id': '17845962995194100'}, {'caption': 'Union Home Minister amitshahofficial’s visit to Delhi government run LNJP hospital, which was in news recently for poor condition of COVID patients, will surely motivate the administration to do better and also comes as a huge relief to the people of Delhi, who have been struggling... #corona #covid19 #india #delhi #bjp', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103423255_148163790127729_5963460060476933287_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=sv5ab-9triYAX8zr8aq&_nc_ht=scontent.cdninstagram.com&oh=3a4d5605332fae1a78efc533215cba3e&oe=5F16366C', 'media_type': 'IMAGE', 'like_count': 42417, 'comments_count': 158, 'timestamp': '2020-06-15T13:57:30+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBdU554gNKp/', 'id': '17948760484349375'}, {'caption': 'You donated and ventilators are here! #PMCARES #thankyou', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82512168_107360344267408_194752731509630725_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=Cd-534nZzWAAX9rQN0E&_nc_ht=scontent.cdninstagram.com&oh=93b694f11ee3985b6d5417f7e1bf67bb&oe=5F174E7D', 'media_type': 'IMAGE', 'like_count': 82829, 'comments_count': 842, 'timestamp': '2020-06-14T18:12:04+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBbNPcTgnAg/', 'id': '17892137323548652'}, {'caption': 'HM Shri amitshahofficial chairs meeting to review COVID-19 situation in Delhi. • Modi govt to immediately provide 500 converted rail coaches to the Delhi govt, adding 8,000 beds for COVID-19 patients. • Testing to double in 2 days and treble in 6 days. #corona #covid19 #delhi #india #bjp', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104218735_113841486841448_3291412899190214212_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=ta2T0QsVNBcAX-S4DpM&_nc_ht=scontent.cdninstagram.com&oh=40bbc553621b2432464f7e346925cf33&oe=5F1518DD', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 40060, 'comments_count': 108, 'timestamp': '2020-06-14T17:59:27+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBbLzDvgV9E/', 'id': '18038595586259710'}, {'caption': "'Sabka Saath' \nSabka Vikas,\nSabka Vishwas,\nin action and spirit. #SamajikSamarasta", 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103509872_113653220191611_5932068315779119246_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=yYeyVsoBTFQAX_YuPeb&_nc_ht=scontent.cdninstagram.com&oh=3479ee1c0360c05739a61658f78c281b&oe=5F14B5BC', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 19663, 'comments_count': 212, 'timestamp': '2020-06-13T06:05:05+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBXVQC2gJCJ/', 'id': '17861022121945904'}, {'caption': 'Modi Government is providing better lifestyle, security and rights to minorities, children and the persecuted. \nBy means of fair justice and equality, it is building a New India that gives a level playing field to everyone. #minorities #security #children #SamajikSamarasta', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82213218_3605854582775422_2878777493708641606_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=jiJYDo8Jyd8AX8_mUxq&_nc_ht=scontent.cdninstagram.com&oh=d83ef5bcbc7821c9b98e46780401aab9&oe=5F164B53', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 18600, 'comments_count': 105, 'timestamp': '2020-06-13T05:30:28+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBXRScAAVZJ/', 'id': '17856215609027235'}, {'caption': 'देश की स्वतंत्रता के लिए अपने प्राणों की आहुति देने वाले अमर शहीद पं. राम प्रसाद बिस्मिल जी की जयंती पर शत्-शत् नमन।', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103365587_565758700709634_7405577148654248981_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=EoKTsl_H-7wAX9oVLA6&_nc_ht=scontent.cdninstagram.com&oh=e75afe2dafb331840778b4c928473230&oe=5F14D832', 'media_type': 'IMAGE', 'like_count': 25150, 'comments_count': 180, 'timestamp': '2020-06-11T06:29:28+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBSOc4hgiSw/', 'id': '17997905677288721'}, {'caption': 'Development of India’s Gateway to the East, the Northeast, has been one of the major revolutions brought by the Modi government.\n\nA look at several such measures and work done... #newnortheast', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103185094_253745506071244_8212898175183513492_n.jpg?_nc_cat=102&_nc_sid=8ae9d6&_nc_ohc=7rb2QQm7ocAAX-Qs-LK&_nc_ht=scontent.cdninstagram.com&oh=2e8fbf1bc10abe71169ef6826606f5a2&oe=5F147696', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 19302, 'comments_count': 77, 'timestamp': '2020-06-11T03:24:27+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBR5RwBgs3V/', 'id': '18104000863182004'}, {'caption': "Modi government has always taken special care of India's flora and fauna. This has resulted in the rise in population of the majestic Asiatic Lion, living in Gujarat’s Gir Forest, by almost 29%. Geographically, the distribution area rose by 36%. India is the home to Asiatic Lion, and kudos to the hardwork of the people who keep their lives safe.", 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102879900_744323092985160_6731549785779784998_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=968gkWmvZ9UAX_cTSIw&_nc_ht=scontent.cdninstagram.com&oh=2ec6b3dc3295269c5bbbd0204c6fb909&oe=5F14303E', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 55072, 'comments_count': 322, 'timestamp': '2020-06-10T14:23:36+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBQf6pqgplm/', 'id': '17860584838943065'}, {'caption': 'People from across the world tuned in to watch the virtual rally of Shri amitshahofficial\n#BanglarJanasamabesh', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102722209_2605887319654066_5107787965378137175_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=IiQil-MWR6YAX_KIJV1&_nc_ht=scontent.cdninstagram.com&oh=d3068f273e58748b6836679eaf90441d&oe=5F17C9E1', 'media_type': 'IMAGE', 'like_count': 57826, 'comments_count': 388, 'timestamp': '2020-06-09T09:55:46+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBNceHcgl6R/', 'id': '17874951385728643'}, {'caption': 'महान स्वतंत्रता सेनानी एवं जननायक भगवान बिरसा मुंडा जी की पुण्यतिथि पर विनम्र श्रद्धांजलि।', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103280597_3057825094254797_3884304578204713535_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=jqN4UkGWW_kAX8XLrPR&_nc_ht=scontent.cdninstagram.com&oh=e1e1ed4e64c49abc7623e75857390a13&oe=5F168630', 'media_type': 'IMAGE', 'like_count': 35190, 'comments_count': 170, 'timestamp': '2020-06-09T06:33:14+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBNFSrDgIIR/', 'id': '17843311712229115'}, {'caption': 'Odisha #BJPJanSamvad in pictures...', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102688611_111240973800675_3675080288425326366_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=gH6s-vPJf78AX-tKsF5&_nc_ht=scontent.cdninstagram.com&oh=8d4d7af55f801525aaabdd2752c0b813&oe=5F18153E', 'media_type': 'IMAGE', 'like_count': 33874, 'comments_count': 203, 'timestamp': '2020-06-08T17:25:45+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBLrK_Zgc69/', 'id': '18056941192242702'}, {'caption': 'बिहार के जन-जन ने सुनी #बिहार_जनसंवाद रैली...', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102705657_274392950281791_8017325389862027533_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=gucFSfG15pgAX-wrFMW&_nc_ht=scontent.cdninstagram.com&oh=a9e66393c568ae5386b05ca989e76020&oe=5F17EEB4', 'media_type': 'IMAGE', 'like_count': 44691, 'comments_count': 349, 'timestamp': '2020-06-07T18:23:54+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBJNCFCABHg/', 'id': '17850850097105388'}, {'caption': 'BJP National President Shri jpnaddaofficial plants a sapling on #WorldEnvironmentDay.', 'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/103183755_832763770583557_8700377016758320263_n.mp4?_nc_cat=107&vs=17948495521346275_1104447547&_nc_vs=HBksFQAYJEdJdDFKZ1lGT3Jyc1pQVUNBSWM4MnRmTThyMTRia1lMQUFBRhUAAsgBABUAGCRHTzd5SWdibE9fNTlKVEFMQVBqaFgzQ1lUbEV3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsbYi6P4g%2BI%2FFQIoAkMzLBdAOAi0OVgQYhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=pqswPNjUho8AX8gpj3q&_nc_ht=video.fdel1-2.fna&oh=6301d7e55708b8a2264ab6cac9877cc3&oe=5F1740C6&_nc_rid=f9f39f2727', 'media_type': 'VIDEO', 'like_count': 26635, 'comments_count': 211, 'timestamp': '2020-06-05T08:22:51+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBC-o0PA69a/', 'id': '18118938049113698'}, {'caption': "I wish I could be there for what has become the famous 'Modi hug' & have my share of samosas. Next time, it will have to be the Gujarati Khichdi. I will try that in the kitchen before next time we meet in person: Australian PM scottmorrisonmp\n.\n.\nPM narendramodi and Australian PM scottmorrisonmp address 1st virtual India-Australia summit. #india #modihug #bjp #australia", 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/101815786_689123381939267_7050305340797946967_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=KqRBMzlminEAX9ZME2p&_nc_ht=scontent.cdninstagram.com&oh=782d2ca5255b711b8bb4f04560811484&oe=5F1506E5', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 106232, 'comments_count': 518, 'timestamp': '2020-06-04T07:58:59+0000', 'owner': {'id': '17841400193077467'}, 'permalink': 'https://www.instagram.com/p/CBAXIaAFEwv/', 'id': '17867225362830120'}], 'paging': {'cursors': {'after': 'QVFIUld1RXRSRWF5X185MmlsN3R5ekY3emMyX2xSWGZAHMlRGYzdzWnRKOGc4QUVkaWM4SzF0ZAmtaZAXdORXBFOW55N1NlZA0o3UU9xalB1NkhDM2VTNk1kWUhB'}}}}, 'id': '17841429540183149'}, {'error': {'message': 'Invalid user id', 'type': 'OAuthException', 'code': 110, 'error_subcode': 2207013, 'is_transient': False, 'error_user_title': 'Cannot find user', 'error_user_msg': 'The user with username: shiromaniakalidal_ cannot be found.', 'fbtrace_id': 'ANHRG5xvKbrpKcOihqlXGhV'}}, {'business_discovery': {'biography': "The Indian National Congress is the world's largest democratic political organisation", 'followers_count': 737046, 'follows_count': 51, 'id': '17841400292397696', 'ig_id': 1132553746, 'media_count': 2533, 'name': 'Congress', 'profile_picture_url': 'https://scontent.fdel1-1.fna.fbcdn.net/v/t51.2885-15/11254462_805774982872629_2023861758_a.jpg?_nc_cat=1&_nc_sid=86c713&_nc_ohc=1eRpneX3ZRYAX8AamgZ&_nc_ht=scontent.fdel1-1.fna&oh=6049b803ae9f7124486208b5c9c0bd53&oe=5F145ED5', 'username': 'incindia', 'website': 'http://www.inc.in/', 'media': {'data': [{'caption': 'देश प्रधानमंत्री की बात पर विश्वास करे या रक्षामंत्री की? #BJP सरकार देश के सामने स्थिति स्पष्ट करने की जगह देश को गुमराह कर रही है। #IndiaDeservesToKnow', 'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104170427_581378116107364_1338460485505880072_n.mp4?_nc_cat=104&vs=17857155890030532_2089826005&_nc_vs=HBksFQAYJEdMdUROUVprUEJla3doQUNBQWlRZVZpNEtwTVNia1lMQUFBRhUAAsgBABUAGCRHQVR3T2daeFA2RWE1ZkFBQUZCX3hYWkdCS3hhYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFoilqvCiv7g%2FFQIoAkMzLBdARi752yLQ5RgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=rSWZksHpYRQAX877H4T&_nc_ht=video.fdel1-2.fna&oh=e183c761ccb0c1fe4b62d6e9d8f31f5c&oe=5F17A2A5&_nc_rid=e3554a25f1', 'media_type': 'VIDEO', 'like_count': 1270, 'comments_count': 28, 'timestamp': '2020-06-22T09:12:09+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBu1xhQpKI4/', 'id': '18104685928149130'}, {'caption': 'This picture speaks louder than our current PM’s silence (Smt. #IndiraGandhi addressing Army jawans at #GalwanValley, Ladakh)\n.\n.\n.\n#Throwback\n#BnW', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104379239_140762534313755_2235825037415171921_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=xTLgALYAhbAAX9dHYtN&_nc_ht=scontent.cdninstagram.com&oh=65c84a824ceb9a57262b868579fb1a8f&oe=5F171C07', 'media_type': 'IMAGE', 'like_count': 9532, 'comments_count': 95, 'timestamp': '2020-06-22T06:26:41+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBui4DaJLlX/', 'id': '18054200188245210'}, {'caption': '“#Yoga includes non-violence, truthfulness, continence etc. It is an avoidance of malice and hatred.” - #JawaharlalNehru \n#InternationalYogaDay', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105978195_574792486808444_5964043191718885735_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=i7mb5u2Onk4AX9hCTRa&_nc_ht=scontent.cdninstagram.com&oh=9d8f5a5d5f077c9b980ab99cce19a6b3&oe=5F15BD16', 'media_type': 'IMAGE', 'like_count': 12628, 'comments_count': 117, 'timestamp': '2020-06-21T04:32:11+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBrw-kzpebW/', 'id': '17845671716204236'}, {'caption': "Even the PMO isn't confident about what the PM says - hence the contradiction in the statements. \n#ModiSurrendersToChina\n#PMModi", 'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104421471_944966139282193_4849825040051136349_n.mp4?_nc_cat=100&vs=17924277823408978_3068789049&_nc_vs=HBksFQAYJEdGOVlPUVlSZ3c0VGNWc0RBRjNuQ3E4dENrNURia1lMQUFBRhUAAsgBABUAGCRHTW5ZUHdiX214LVZxb2tLQUl2dDVkQm9weTlPYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFqSYs52kgtc%2FFQIoAkMzLBdASK752yLQ5RgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=PHbHWRTM__8AX81_wbb&_nc_ht=video.fdel1-4.fna&oh=b074e6b75043b8208176ce6a1c61ed12&oe=5F169B79&_nc_rid=068de58f0b', 'media_type': 'VIDEO', 'like_count': 3746, 'comments_count': 191, 'timestamp': '2020-06-20T10:34:24+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBp1liMp3AV/', 'id': '17856319280045951'}, {'caption': 'To capitalise on opportunities in the midst of challenges, one needs to have a courageous and indomitable spirit. Leaders with such virtues have led our Nation to sail through many challenges of the past.\n\n#CongressKeVichaar', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104110830_715822572527746_3061748498572975866_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=pHSiY52MUXcAX_upLxR&_nc_ht=scontent.cdninstagram.com&oh=1ea8f64fe44c160d3b69b56df38264be&oe=5F1656F1', 'media_type': 'IMAGE', 'like_count': 8275, 'comments_count': 53, 'timestamp': '2020-06-20T05:18:51+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBpRhkqpZmx/', 'id': '17903003914468339'}, {'caption': 'इस सत्ता को चुभते हैं कुछ सवाल\nसवाल जो नाकामी पर प्रहार करे\nसवाल जो कपटी नीयत पर वार करे\nसवाल जो जनता के हितों का ख्याल करे\n\nये सवाल जारी रहेंगे...जनता के लिए', 'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104341014_305967440410145_1099334899577466953_n.mp4?_nc_cat=105&vs=18145461115012617_1088922159&_nc_vs=HBksFQAYJEdCWWVPQVloTnBtWVJoWUJBRWt3Z1VKRW4wRVBia1lMQUFBRhUAAsgBABUAGCRHTVNjU1Fhc2w4enVfckFDQURsaHZSWVo3Q2doYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpKItLfrzLtAFQIoAkMzLBdATMRaHKwIMRgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=SBa7o57dfHYAX-rhdrP&_nc_ht=video.fdel1-4.fna&oh=46c9061b092fc9c0d2a9f1c86fdbe980&oe=5F158203&_nc_rid=81d2e1a6ff', 'media_type': 'VIDEO', 'like_count': 3330, 'comments_count': 186, 'timestamp': '2020-06-19T08:30:35+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBnClI1JFLI/', 'id': '17877163132696478'}, {'caption': 'Democracy is the expression of the will and wants of each and every citizen.\nrahulgandhi', 'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104019342_533121284234120_7863874374787307682_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=i8GyrqTz60wAX-NCXCq&_nc_ht=scontent.cdninstagram.com&oh=2424b2c000b5d3e63d210484ad52dc8a&oe=5F175E75', 'media_type': 'IMAGE', 'like_count': 23632, 'comments_count': 432, 'timestamp': '2020-06-19T03:46:43+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBmiL0opg8E/', 'id': '17905494460469907'}, {'caption': 'जो दुस्साहस चीन ने 53 साल में नहीं किया, उसकी आज इतनी हिम्मत कैसे हो गई?\n\n#TreacherousChina', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103673029_150948893177181_8536056608291036250_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=utR5zwsvPe0AX8fTRDF&_nc_ht=scontent.cdninstagram.com&oh=006d403cc0b1d4c487a8e2deed28f309&oe=5F168C8D', 'media_type': 'IMAGE', 'like_count': 9971, 'comments_count': 348, 'timestamp': '2020-06-18T12:52:03+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBk7zH2pEzG/', 'id': '17904411436467397'}, {'caption': 'Why were our soldiers unarmed amidst rising tensions at the border? \n#TreacherousChina', 'media_url': 'https://video.fdel1-3.fna.fbcdn.net/v/t50.2886-16/103917597_268067667765368_3204911130508031090_n.mp4?_nc_cat=108&vs=17868882598827351_1061274239&_nc_vs=HBksFQAYJEdCMm9NUVo0NkJ4ZXp2TUFBSEowb0Y2eElYb3Nia1lMQUFBRhUAAsgBABUAGCRHRjYtT0FhcW0tTGNrZklBQUhiVnVFbHJfZk01YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFq72l9jt6b0%2FFQIoAkMzLBdASBm6XjU%2FfRgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=qGnk6AJtEf8AX8U5-nZ&_nc_ht=video.fdel1-3.fna&oh=baa8ad0a9e169a456630c5b47170523c&oe=5F1527AE&_nc_rid=f7be91fa0c', 'media_type': 'VIDEO', 'like_count': 3875, 'comments_count': 70, 'timestamp': '2020-06-18T10:48:25+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBktnFmJFK8/', 'id': '17862680728930154'}, {'caption': '20 of our brave hearts have been martyred at the hands of the Chinese Army. How dare #China intrude in our territory & kill our unarmed soldiers? \n#TreacherousChina\n\u2069', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103017304_203860697430564_3470571377145949547_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=woFl8POdDi4AX83d-pz&_nc_ht=scontent.cdninstagram.com&oh=7e1fdc3b8d2aba221d2ee7f816d040fc&oe=5F16EADC', 'media_type': 'IMAGE', 'like_count': 14096, 'comments_count': 534, 'timestamp': '2020-06-18T08:39:44+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBke7GVpIhV/', 'id': '17842167746258136'}, {'caption': "As India gets elected for its 8th term in #UNSC, it fills our hearts with pride that once again Indians will be showing the way to the world. This is a testament to India's long standing commitment towards humanitarian & democratic development in the world.\n#Congratulations", 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103912973_704697520331991_308671631639705721_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=SOwiY9B7Of8AX-UM7AP&_nc_ht=scontent.cdninstagram.com&oh=7aeab2651d055c27808dcdcf15ce804b&oe=5F1788BE', 'media_type': 'IMAGE', 'like_count': 8670, 'comments_count': 75, 'timestamp': '2020-06-18T07:39:34+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBkYCcrJPEJ/', 'id': '17944627336360538'}, {'caption': 'In this hour of crisis, let it be known that we as Indians have, are and will always stand together to uphold the sovereignty and integrity of our Nation.\n\n#CongressKeVichaar', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104038648_721832735309182_5848102739931651506_n.jpg?_nc_cat=101&_nc_sid=8ae9d6&_nc_ohc=xcBLoVzGMR8AX8Sk04D&_nc_ht=scontent.cdninstagram.com&oh=dd957d17ba4884ac6995908b2e176db7&oe=5F17D118', 'media_type': 'IMAGE', 'like_count': 5925, 'comments_count': 81, 'timestamp': '2020-06-18T04:53:21+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBkFA8VpYUw/', 'id': '17877373282716304'}, {'caption': 'हम तो विपक्ष है, आपने क्या किया?\n#PMDaroMatJawabDo', 'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104079278_287809355963460_5751376487412483782_n.mp4?_nc_cat=104&vs=17895105091517602_1093396098&_nc_vs=HBksFQAYJEdLNGZOQVpFM0d6V3dnVUJBTVpHd1hWeC10QlBia1lMQUFBRhUAAsgBABUAGCRHSl9JTkFaM3BDWVJESzhBQUw4RjdzSUFyWWNDYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsTqwJ6a4Mk%2FFQIoAkMzLBdATR3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=BbGrPTp4GEYAX-fzmFd&_nc_ht=video.fdel1-2.fna&oh=8ca48a2713ce60ac85d5f563cc5ee072&oe=5F146086&_nc_rid=51b3dc0763', 'media_type': 'VIDEO', 'like_count': 3829, 'comments_count': 147, 'timestamp': '2020-06-17T09:04:56+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBh864upBX-/', 'id': '18033535909265073'}, {'caption': 'Where are these leaders when the nation needs them?\n\n#PMDaroMatJawabDo\n#PMModi\n#AmitShah\n#RajnathSingh', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103834579_138958684473650_3142810146740029834_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=ZZVChNbQlq0AX-zQhb3&_nc_ht=scontent.cdninstagram.com&oh=a75d217fefa016dcabcf815b0a2ef246&oe=5F146927', 'media_type': 'IMAGE', 'like_count': 9941, 'comments_count': 226, 'timestamp': '2020-06-17T08:44:35+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBh6rrIJg3I/', 'id': '17900795782494345'}, {'caption': 'A message for our brave martyrs from Shri rahulgandhi .\n\nदेश के वीर शहीदों को श्री rahulgandhi  का सलाम।', 'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104468298_1246363379047041_4560505356078130524_n.mp4?_nc_cat=104&vs=18053319322246534_3604319899&_nc_vs=HBksFQAYJEdFb1BPZ2FCR25pV2oyMEVBRnlsVFhGMUswby1ia1lMQUFBRhUAAsgBABUAGCRHTUFGTHdaY3Nfd0UxamtJQU9uczhxX1RqUDlsYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFoyVzMG92ZFAFQIoAkMzLBdAO0RaHKwIMRgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=Kp2nuUIwkO8AX_crZ3B&_nc_ht=video.fdel1-2.fna&oh=15bfdc61d5a417b4401ed68d6bf843a1&oe=5F15FBE4&_nc_rid=d857af00f9', 'media_type': 'VIDEO', 'like_count': 12603, 'comments_count': 306, 'timestamp': '2020-06-17T05:59:04+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBhnj3Mpme6/', 'id': '18149144914051751'}, {'caption': 'These price increases are saddling our people with an additional burden of this enormous magnitude that is neither justified nor appropriate: Congress President Smt. #SoniaGandhi. \n#ModiStopLootingIndia', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103886495_263708551575751_5394649116907206411_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=AkK0d9Y5BYMAX9g-_kg&_nc_ht=scontent.cdninstagram.com&oh=f6e18174f8cfe19b12b66ed952b3ae14&oe=5F17990C', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 10334, 'comments_count': 161, 'timestamp': '2020-06-16T11:37:28+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBfprGwDEd-/', 'id': '18122549761102846'}, {'caption': 'Congress President Smt. #SoniaGandhi writes to the Prime Minister urging the govt to immediately roll back hikes on #FuelPrices & pass the benefit of low crude oil prices to the citizens.', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104017706_2488773548011810_1911958886266898770_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=4zJf4fXOUdYAX83Z5ai&_nc_ht=scontent.cdninstagram.com&oh=6d66b424724b40515ea43be7ee9ca1e9&oe=5F14FB8A', 'media_type': 'CAROUSEL_ALBUM', 'like_count': 7417, 'comments_count': 92, 'timestamp': '2020-06-16T04:40:19+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBe57ygjCSU/', 'id': '17852758913089264'}, {'caption': 'Tolerance has been one of the foundational principles of this Nation from time immemorial. To uphold this principle is the duty of each patriotic citizen.\n\n#CongressKeVichaar', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104167649_1157244254635556_6572278063820412279_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=YeM889avZLIAX9OcB90&_nc_ht=scontent.cdninstagram.com&oh=641e3ec90252b412dba213d0c1a753fd&oe=5F1774F2', 'media_type': 'IMAGE', 'like_count': 4305, 'comments_count': 27, 'timestamp': '2020-06-16T04:21:17+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBe3wayDKU7/', 'id': '17871688270778317'}, {'caption': "Each Indian's unwavering dedication to uphold the democratic values enshrined in our Constitution has allowed the India of our forefathers’ dreams to be a reality today. Any attempt to subvert these values will always be rejected.\n\n#CongressKeVichaar", 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103552497_943621902726943_5910493528061038295_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=eEY935g0tHwAX9e_AR8&_nc_ht=scontent.cdninstagram.com&oh=60bea97bbe9b31800b33d50a1a6d0a50&oe=5F154BE0', 'media_type': 'IMAGE', 'like_count': 5675, 'comments_count': 15, 'timestamp': '2020-06-15T04:34:42+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBcUfufJlFC/', 'id': '17860886134927103'}, {'caption': 'We are deeply shocked & saddened to hear about the untimely demise of the young & talented actor, #SushantSinghRajput. Our thoughts and prayers are with his family & friends in this time of grief.\n\nAs a nation we need to be more forthcoming about #MentalHealth. We need to talk about it, we need to create policies for it & we need to break the stigma around it. For the sake of our youth & our future, we must acknowledge the problem.', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103414571_274786153763653_2212772926284413363_n.jpg?_nc_cat=101&_nc_sid=8ae9d6&_nc_ohc=jX0SJcmEfXEAX_7olzF&_nc_ht=scontent.cdninstagram.com&oh=aafe3476cc867dfc64b66fc8bec10915&oe=5F152AEF', 'media_type': 'IMAGE', 'like_count': 31624, 'comments_count': 262, 'timestamp': '2020-06-14T12:36:17+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBam0KMpYbd/', 'id': '17855599691047430'}, {'caption': 'Some individuals attain fame due to their posturing, while others turn out to be valuable assets to the Nation because of their true devotion towards fellow citizens and their unrelenting dedication towards society.\n\n#CongressKeVichaar', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104161617_180247470109302_1314394772295479767_n.jpg?_nc_cat=106&_nc_sid=8ae9d6&_nc_ohc=4UZl0am5wHgAX-SmYd4&_nc_ht=scontent.cdninstagram.com&oh=8e4ac6303898e51fe197fcf071bb7e0d&oe=5F142E15', 'media_type': 'IMAGE', 'like_count': 7336, 'comments_count': 51, 'timestamp': '2020-06-14T04:32:33+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBZvdHfpwrp/', 'id': '17844128282222131'}, {'caption': "Rising #FuelPrices are hurting the common man and here's what the PM had to say about it.\n#YaadRakhna", 'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/103716284_266938251314575_2593447021927970981_n.mp4?_nc_cat=104&vs=17910903625449107_2559638764&_nc_vs=HBksFQAYJEdMeVZMZ2FQaGFWbngtSUFBS1c0ejJWVHh2MGpia1lMQUFBRhUAAsgBABUAGCRHSi1xTEFhcENVNVltWU1GQUlqdG1kWWJCZFF6YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFqaU3M%2Fm99A%2FFQIoAkMzLBdATeaHKwIMShgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=bF6Jh5eTWrQAX854-_k&_nc_ht=video.fdel1-2.fna&oh=2788f030d97eac8a8d4fd25601b53961&oe=5F16273C&_nc_rid=6c01f6bbd0', 'media_type': 'VIDEO', 'like_count': 3825, 'comments_count': 135, 'timestamp': '2020-06-13T05:32:33+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBXRdlOpSGp/', 'id': '17865319783844070'}, {'caption': 'It is the prime duty of elected representatives to ensure that citizens are enabled and their demands met. When a deaf ear is turned on the citizens, democracy fails.\n\n#CongressKeVichaar', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103846199_2601239240189763_7309523997967586898_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=w6bpGGjCZG0AX_HfbAL&_nc_ht=scontent.cdninstagram.com&oh=516215677cbf67c206a049e05289adaa&oe=5F153747', 'media_type': 'IMAGE', 'like_count': 9437, 'comments_count': 107, 'timestamp': '2020-06-13T04:26:09+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBXJ7ddpfvG/', 'id': '17852090282101150'}, {'caption': "Here's your chance to become a warrior & highlight issues that trouble you. Send us your videos at SpeakupIndia@inc.in and not only will we highlight the best videos but also provide a chance to consistent campaigners to be the voice of INC as a media panelist.\n#SpeakUpWarriors", 'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/102343403_282631239458142_7369783365241382702_n.mp4?_nc_cat=102&vs=17853839684071931_1617264121&_nc_vs=HBksFQAYJEdPdWlHUVplWGFFMkRRRUJBQzZueTRUc3VrWm1ia1lMQUFBRhUAAsgBABUAGCRHSWYySndhbnZIVXVQRE1CQUctd2pvdU85V1VzYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFva%2Fov%2Be%2FrY%2FFQIoAkMzLBdAR0ztkWhysBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=dNJdyoGPbXEAX9xKj-B&_nc_ht=video.fdel1-4.fna&oh=6be0b2d947b17ff5d132528522ed8d90&oe=5F144F94&_nc_rid=582444fb77', 'media_type': 'VIDEO', 'like_count': 2369, 'comments_count': 29, 'timestamp': '2020-06-12T14:00:32+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBVm03-pzEP/', 'id': '17857925329990640'}, {'caption': 'Indian American community is a real asset to both countries. This is a shared property. This is a good relationship: Shri rahulgandhi \n#RahulGandhiStandswithPeople', 'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103853363_260794248479349_5177715456952293196_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=wBeq76RJkYcAX_YSSOA&_nc_ht=scontent.cdninstagram.com&oh=7f1b1218de372e472e7cc10cc9a9a7a9&oe=5F152D13', 'media_type': 'IMAGE', 'like_count': 7566, 'comments_count': 112, 'timestamp': '2020-06-12T11:12:14+0000', 'owner': {'id': '17841400292397696'}, 'permalink': 'https://www.instagram.com/p/CBVTmu2JIXq/', 'id': '17873803132730481'}], 'paging': {'cursors': {'after': 'QVFIUlBXZAFc1NXpUeklibUplVHJ5bUN3YVYyNHVJSWVkRzhJOWNYcDR6blJSRndFZA0xJSFc1c08ta1NnRTAxVFZAPUnI0UjZAfTWg1a1RYcjVSUUp0TkFwamdR'}}}, 'recently_searched_hashtags': {'data': [{'id': '17843783248059507'}], 'paging': {'cursors': {'before': 'QVFIUlFMYlJjckpJbnJ4amtpRlhad011LV9Gb3N6UjhYYUl5UGRXUUluTEZApSXpUVnc3cFBhTC12WXJTMUNMeXRDRzgwUGdWMmRUMVgtaXZATdFFzeTJvTlNn', 'after': 'QVFIUlFMYlJjckpJbnJ4amtpRlhad011LV9Gb3N6UjhYYUl5UGRXUUluTEZApSXpUVnc3cFBhTC12WXJTMUNMeXRDRzgwUGdWMmRUMVgtaXZATdFFzeTJvTlNn'}}}}, 'id': '17841429540183149'}]
    


```python
x[0]
```




    {'business_discovery': {'biography': "Bharatiya Janata Party, founded in 1980, is World's largest political party. It currently leads the NDA, which is governing India.  #BJP  #India",
      'followers_count': 3297381,
      'follows_count': 0,
      'id': '17841400193077467',
      'ig_id': 1757894435,
      'media_count': 3616,
      'name': 'BJP - Bharatiya Janata Party',
      'profile_picture_url': 'https://scontent.fdel1-1.fna.fbcdn.net/v/t51.2885-15/22858431_375803636191252_1114185658420690944_n.jpg?_nc_cat=1&_nc_sid=86c713&_nc_ohc=_8aTjRZ5dpkAX-dVRH1&_nc_ht=scontent.fdel1-1.fna&oh=70678535e7f38bc275480ff154a4e85b&oe=5F15917D',
      'username': 'bjp4india',
      'website': 'https://www.bjp.org/membership',
      'media': {'data': [{'caption': 'लड़ाई जारी है लेकिन हौसले बुलंद है। जीतेंगे हम...',
         'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/105281340_196641258291866_7205467741881983526_n.mp4?_nc_cat=100&vs=17869559734829517_3228560770&_nc_vs=HBksFQAYJEdEeDNSZ2FhUWxrYzJMSUFBQ1ppYVN1ODl2NWpia1lMQUFBRhUAAsgBABUAGCRHTWphT1FiZzRlMjRVdzREQU1CUFp5T05uVVVJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpq8%2BtOikb4%2FFQIoAkMzLBdAPirAgxJumBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=AW8hg-F_MkIAX_4qXXe&_nc_ht=video.fdel1-4.fna&oh=177c7874d52c3b0a600436b702aa01b1&oe=5F1767E5&_nc_rid=0b3942b744',
         'media_type': 'VIDEO',
         'like_count': 16018,
         'comments_count': 66,
         'timestamp': '2020-06-22T05:48:45+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBuegpTAQRn/',
         'id': '17863465609926295'},
        {'caption': 'BJP National President Shri jpnaddaofficial performs yoga at his residence on #InternationalYogaDay today. #MyLifeMyYoga',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104053466_2317964778511660_5981624510555492019_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=JUPXH3DmOxMAX8y1O3N&_nc_ht=scontent.cdninstagram.com&oh=0a19fa241fd1c3d68c7856f2ca2b2a75&oe=5F15DE50',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 63768,
         'comments_count': 148,
         'timestamp': '2020-06-21T04:02:50+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBrtnoggN_k/',
         'id': '18059996809227284'},
        {'caption': 'कोरोना के संकटकाल में भी टेक्नोलॉजी के माध्यम से देश के जन-जन तक पहुंच रही है भारतीय जनता पार्टी। आज भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial के राजस्थान जनसंवाद रैली में संबोधन को सुनते आमजन।',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105414284_265420581539185_4630206849005528189_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=Hxn-B9z-d0EAX_IB2AH&_nc_ht=scontent.cdninstagram.com&oh=e719ea92eab6f1b1961397dfb105502e&oe=5F157E9D',
         'media_type': 'IMAGE',
         'like_count': 34851,
         'comments_count': 118,
         'timestamp': '2020-06-20T13:37:31+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBqKlz4ASym/',
         'id': '18091724080175849'},
        {'caption': 'राहुल गांधी, सुनिए हमारे वीर जवान के वीर पिता की भावनाओं को और बंद कीजिए उनके नाम पर निकृष्ट राजनीति। #india #bjp #china',
         'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104735923_1188447364835330_3114894258955085295_n.mp4?_nc_cat=100&vs=17877093337693291_566229461&_nc_vs=HBksFQAYJEdMTWtQZ1lDNkFQMzRqZ0VBTy1sNnpuVFV6b3Jia1lMQUFBRhUAAsgBABUAGCRHR0NaT1FhUWRuQ1BreVlCQU1XdXdwd1V0UmtJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFtaZosnkx8E%2FFQIoAkMzLBdAQEiTdLxqfxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=0REsp84tcW8AX9F6h3j&_nc_ht=video.fdel1-4.fna&oh=1159a1ac7de66f95cd74591ff9055f93&oe=5F1764F9&_nc_rid=7c1a08f482',
         'media_type': 'VIDEO',
         'like_count': 19614,
         'comments_count': 179,
         'timestamp': '2020-06-20T05:01:07+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBpPeZxAd5z/',
         'id': '17887502845575049'},
        {'caption': 'भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial 20 जून 2020 को दोपहर 12.30 बजे वीडियो कॉन्फ़्रेंसिंग के माध्यम से राजस्थान जनसंवाद रैली को संबोधित करेंगे। BJP4Rajasthan',
         'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104265490_292049665296242_423465061768528093_n.mp4?_nc_cat=107&vs=17857036247024519_3284310992&_nc_vs=HBksFQAYJEdCTDNOZ1p5aDQ0Y25na0JBTjJBZ09VNmNfQUZia1lMQUFBRhUAAsgBABUAGCRHSDZYT0FZS0hFWklvLUVBQUc5Y3c3ZmJrMlpvYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFo7X66enuLg%2FFQIoAkMzLBdANV3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=saabCtPvwukAX83CWTS&_nc_ht=video.fdel1-2.fna&oh=4f35aada4816b6b365a2b0446cc5a66f&oe=5F15A1C1&_nc_rid=4ea34c4e61',
         'media_type': 'VIDEO',
         'like_count': 16005,
         'comments_count': 44,
         'timestamp': '2020-06-19T17:11:30+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBn-QQ9FWKa/',
         'id': '18152066587031624'},
        {'caption': 'PM narendramodi holds All Party Meeting to discuss situation in India-China border areas\n.\n.\n20 of our brave soldiers made the supreme sacrifice in Ladakh but also taught a lesson to those who dared to look towards our motherland. Neither is anyone inside our territory nor is any of our post captured; India wants peace and friendship, but upholding sovereignty is foremost: PM narendramodi',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104101998_579856346007751_1019788892395299541_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=tacps046vWcAX8u0QB2&_nc_ht=scontent.cdninstagram.com&oh=ec16af88a1bad743b7948aea877bc480&oe=5F17339C',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 88308,
         'comments_count': 319,
         'timestamp': '2020-06-19T16:36:37+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBn6Sz0gg-V/',
         'id': '17888904943571172'},
        {'caption': "Modi govt's huge relief to Delhiites. \nOn instructions of Home Minister Shri amitshahofficial, the cost of treatment of COVID-19 patients in private hospitals of Delhi has been reduced by about two-thirds.\n\nPPE kits and medicines are also included in the new rates.",
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105020102_191367085579754_6719776562378654198_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=cUJkZK9oWeUAX8bCrdX&_nc_ht=scontent.cdninstagram.com&oh=9c5485f63f3e7558279e69169bcc28b2&oe=5F16869C',
         'media_type': 'IMAGE',
         'like_count': 28970,
         'comments_count': 269,
         'timestamp': '2020-06-19T13:26:29+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBnkiO9gXcK/',
         'id': '17875144507732012'},
        {'caption': 'BJP has decided to postpone all its political programmes including virtual rallies for next 2 days.',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104103516_103667658011266_3962349400865496458_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=SrzDIB3ShaYAX9rdr23&_nc_ht=scontent.cdninstagram.com&oh=3370eb484c2794f990b23eb2f3b8b697&oe=5F1733FD',
         'media_type': 'IMAGE',
         'like_count': 23698,
         'comments_count': 145,
         'timestamp': '2020-06-18T06:09:47+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBkNw3AAJ0A/',
         'id': '18121635580113888'},
        {'caption': '1857 के प्रथम स्वतंत्रता संग्राम में अंग्रेज़ी शासन के विरुद्ध अग्रिम भूमिका निभाकर अपने प्राणों की आहुति देने वाली महान वीरांगना रानी लक्ष्मीबाई की पुण्यतिथि पर कोटि-कोटि नमन।',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103661980_566983254001582_7367512126551480632_n.jpg?_nc_cat=108&_nc_sid=8ae9d6&_nc_ohc=C5KmytflgHYAX-jQdzx&_nc_ht=scontent.cdninstagram.com&oh=cb83d40338ed9cd684123c8b47109659&oe=5F16ECD6',
         'media_type': 'IMAGE',
         'like_count': 37857,
         'comments_count': 231,
         'timestamp': '2020-06-18T04:33:14+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBkCtskA-wB/',
         'id': '17874635890734764'},
        {'caption': 'भारत शांति चाहता है, लेकिन भारत उकसाने पर हर हाल में यथोचित जवाब देने में सक्षम है। हमारे दिवंगत शहीद वीर जवानों के विषय में देश को इस बात में गर्व होगा कि वे मारते-मारते मरे हैं: प्रधानमंत्री श्री narendramodi',
         'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104485235_2728637797458196_1083507323252640862_n.mp4?_nc_cat=102&vs=17876598496707417_2072603921&_nc_vs=HBksFQAYJEdITlJPZ1lVWWFOX3JyRUpBRjRNQW5vclpBa1Bia1lMQUFBRhUAAsgBABUAGCRHS2YwTmdZQ0lIVjRYQUVKQUFrWHVCYl85Ynd3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFrLqvqv9qsE%2FFQIoAkMzLBdARfeNT987ZBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=JTZii5Y9M0oAX-V7vRo&_nc_ht=video.fdel1-4.fna&oh=8183b16ee1a4786bb958993128c4bfdc&oe=5F15687B&_nc_rid=b66e01f968',
         'media_type': 'VIDEO',
         'like_count': 32520,
         'comments_count': 454,
         'timestamp': '2020-06-17T15:54:43+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBir3VWARag/',
         'id': '18110380408137861'},
        {'caption': "Stay tuned for BJP National President Shri jpnaddaofficial's 'Kerala Jan Samvad Rally' on 16 June 2020.\n\nWatch the live webcast of the virtual rally on all social media platforms of BJP. #BJPJanSamvad",
         'media_url': 'https://video.fdel1-1.fna.fbcdn.net/v/t50.2886-16/103700248_282523916206191_4692889505717351644_n.mp4?_nc_cat=110&vs=17861586256940324_2588048645&_nc_vs=HBksFQAYJEdCaFhMZ1p2Z0tvNTlBQUJBTnowY0RZa2ZpQkJia1lMQUFBRhUAAsgBABUAGCRHQUxOSmdaYUF2SEZBdTRBQUtCOUE1MElmcFF0YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsjOgsyTwbo%2FFQIoAkMzLBdANTvnbItDlhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=66F1LprSIjUAX883oTc&_nc_ht=video.fdel1-1.fna&oh=db5c5e29bd5290dc448e599893fd27cd&oe=5F165617&_nc_rid=9e8615f55b',
         'media_type': 'VIDEO',
         'like_count': 14411,
         'comments_count': 66,
         'timestamp': '2020-06-15T15:43:51+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBdhBXRA31s/',
         'id': '17845962995194100'},
        {'caption': 'Union Home Minister amitshahofficial’s visit to Delhi government run LNJP hospital, which was in news recently for poor condition of COVID patients, will surely motivate the administration to do better and also comes as a huge relief to the people of Delhi, who have been struggling... #corona #covid19 #india #delhi #bjp',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103423255_148163790127729_5963460060476933287_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=sv5ab-9triYAX8zr8aq&_nc_ht=scontent.cdninstagram.com&oh=3a4d5605332fae1a78efc533215cba3e&oe=5F16366C',
         'media_type': 'IMAGE',
         'like_count': 42417,
         'comments_count': 158,
         'timestamp': '2020-06-15T13:57:30+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBdU554gNKp/',
         'id': '17948760484349375'},
        {'caption': 'You donated and ventilators are here! #PMCARES #thankyou',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82512168_107360344267408_194752731509630725_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=Cd-534nZzWAAX9rQN0E&_nc_ht=scontent.cdninstagram.com&oh=93b694f11ee3985b6d5417f7e1bf67bb&oe=5F174E7D',
         'media_type': 'IMAGE',
         'like_count': 82829,
         'comments_count': 842,
         'timestamp': '2020-06-14T18:12:04+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBbNPcTgnAg/',
         'id': '17892137323548652'},
        {'caption': 'HM Shri amitshahofficial chairs meeting to review COVID-19 situation in Delhi. • Modi govt to immediately provide 500 converted rail coaches to the Delhi govt, adding 8,000 beds for COVID-19 patients. • Testing to double in 2 days and treble in 6 days. #corona #covid19 #delhi #india #bjp',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104218735_113841486841448_3291412899190214212_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=ta2T0QsVNBcAX-S4DpM&_nc_ht=scontent.cdninstagram.com&oh=40bbc553621b2432464f7e346925cf33&oe=5F1518DD',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 40060,
         'comments_count': 108,
         'timestamp': '2020-06-14T17:59:27+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBbLzDvgV9E/',
         'id': '18038595586259710'},
        {'caption': "'Sabka Saath' \nSabka Vikas,\nSabka Vishwas,\nin action and spirit. #SamajikSamarasta",
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103509872_113653220191611_5932068315779119246_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=yYeyVsoBTFQAX_YuPeb&_nc_ht=scontent.cdninstagram.com&oh=3479ee1c0360c05739a61658f78c281b&oe=5F14B5BC',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 19663,
         'comments_count': 212,
         'timestamp': '2020-06-13T06:05:05+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBXVQC2gJCJ/',
         'id': '17861022121945904'},
        {'caption': 'Modi Government is providing better lifestyle, security and rights to minorities, children and the persecuted. \nBy means of fair justice and equality, it is building a New India that gives a level playing field to everyone. #minorities #security #children #SamajikSamarasta',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82213218_3605854582775422_2878777493708641606_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=jiJYDo8Jyd8AX8_mUxq&_nc_ht=scontent.cdninstagram.com&oh=d83ef5bcbc7821c9b98e46780401aab9&oe=5F164B53',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 18600,
         'comments_count': 105,
         'timestamp': '2020-06-13T05:30:28+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBXRScAAVZJ/',
         'id': '17856215609027235'},
        {'caption': 'देश की स्वतंत्रता के लिए अपने प्राणों की आहुति देने वाले अमर शहीद पं. राम प्रसाद बिस्मिल जी की जयंती पर शत्-शत् नमन।',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103365587_565758700709634_7405577148654248981_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=EoKTsl_H-7wAX9oVLA6&_nc_ht=scontent.cdninstagram.com&oh=e75afe2dafb331840778b4c928473230&oe=5F14D832',
         'media_type': 'IMAGE',
         'like_count': 25150,
         'comments_count': 180,
         'timestamp': '2020-06-11T06:29:28+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBSOc4hgiSw/',
         'id': '17997905677288721'},
        {'caption': 'Development of India’s Gateway to the East, the Northeast, has been one of the major revolutions brought by the Modi government.\n\nA look at several such measures and work done... #newnortheast',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103185094_253745506071244_8212898175183513492_n.jpg?_nc_cat=102&_nc_sid=8ae9d6&_nc_ohc=7rb2QQm7ocAAX-Qs-LK&_nc_ht=scontent.cdninstagram.com&oh=2e8fbf1bc10abe71169ef6826606f5a2&oe=5F147696',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 19302,
         'comments_count': 77,
         'timestamp': '2020-06-11T03:24:27+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBR5RwBgs3V/',
         'id': '18104000863182004'},
        {'caption': "Modi government has always taken special care of India's flora and fauna. This has resulted in the rise in population of the majestic Asiatic Lion, living in Gujarat’s Gir Forest, by almost 29%. Geographically, the distribution area rose by 36%. India is the home to Asiatic Lion, and kudos to the hardwork of the people who keep their lives safe.",
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102879900_744323092985160_6731549785779784998_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=968gkWmvZ9UAX_cTSIw&_nc_ht=scontent.cdninstagram.com&oh=2ec6b3dc3295269c5bbbd0204c6fb909&oe=5F14303E',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 55072,
         'comments_count': 322,
         'timestamp': '2020-06-10T14:23:36+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBQf6pqgplm/',
         'id': '17860584838943065'},
        {'caption': 'People from across the world tuned in to watch the virtual rally of Shri amitshahofficial\n#BanglarJanasamabesh',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102722209_2605887319654066_5107787965378137175_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=IiQil-MWR6YAX_KIJV1&_nc_ht=scontent.cdninstagram.com&oh=d3068f273e58748b6836679eaf90441d&oe=5F17C9E1',
         'media_type': 'IMAGE',
         'like_count': 57826,
         'comments_count': 388,
         'timestamp': '2020-06-09T09:55:46+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBNceHcgl6R/',
         'id': '17874951385728643'},
        {'caption': 'महान स्वतंत्रता सेनानी एवं जननायक भगवान बिरसा मुंडा जी की पुण्यतिथि पर विनम्र श्रद्धांजलि।',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103280597_3057825094254797_3884304578204713535_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=jqN4UkGWW_kAX8XLrPR&_nc_ht=scontent.cdninstagram.com&oh=e1e1ed4e64c49abc7623e75857390a13&oe=5F168630',
         'media_type': 'IMAGE',
         'like_count': 35190,
         'comments_count': 170,
         'timestamp': '2020-06-09T06:33:14+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBNFSrDgIIR/',
         'id': '17843311712229115'},
        {'caption': 'Odisha #BJPJanSamvad in pictures...',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102688611_111240973800675_3675080288425326366_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=gH6s-vPJf78AX-tKsF5&_nc_ht=scontent.cdninstagram.com&oh=8d4d7af55f801525aaabdd2752c0b813&oe=5F18153E',
         'media_type': 'IMAGE',
         'like_count': 33874,
         'comments_count': 203,
         'timestamp': '2020-06-08T17:25:45+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBLrK_Zgc69/',
         'id': '18056941192242702'},
        {'caption': 'बिहार के जन-जन ने सुनी #बिहार_जनसंवाद रैली...',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102705657_274392950281791_8017325389862027533_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=gucFSfG15pgAX-wrFMW&_nc_ht=scontent.cdninstagram.com&oh=a9e66393c568ae5386b05ca989e76020&oe=5F17EEB4',
         'media_type': 'IMAGE',
         'like_count': 44691,
         'comments_count': 349,
         'timestamp': '2020-06-07T18:23:54+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBJNCFCABHg/',
         'id': '17850850097105388'},
        {'caption': 'BJP National President Shri jpnaddaofficial plants a sapling on #WorldEnvironmentDay.',
         'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/103183755_832763770583557_8700377016758320263_n.mp4?_nc_cat=107&vs=17948495521346275_1104447547&_nc_vs=HBksFQAYJEdJdDFKZ1lGT3Jyc1pQVUNBSWM4MnRmTThyMTRia1lMQUFBRhUAAsgBABUAGCRHTzd5SWdibE9fNTlKVEFMQVBqaFgzQ1lUbEV3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsbYi6P4g%2BI%2FFQIoAkMzLBdAOAi0OVgQYhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=pqswPNjUho8AX8gpj3q&_nc_ht=video.fdel1-2.fna&oh=6301d7e55708b8a2264ab6cac9877cc3&oe=5F1740C6&_nc_rid=f9f39f2727',
         'media_type': 'VIDEO',
         'like_count': 26635,
         'comments_count': 211,
         'timestamp': '2020-06-05T08:22:51+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBC-o0PA69a/',
         'id': '18118938049113698'},
        {'caption': "I wish I could be there for what has become the famous 'Modi hug' & have my share of samosas. Next time, it will have to be the Gujarati Khichdi. I will try that in the kitchen before next time we meet in person: Australian PM scottmorrisonmp\n.\n.\nPM narendramodi and Australian PM scottmorrisonmp address 1st virtual India-Australia summit. #india #modihug #bjp #australia",
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/101815786_689123381939267_7050305340797946967_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=KqRBMzlminEAX9ZME2p&_nc_ht=scontent.cdninstagram.com&oh=782d2ca5255b711b8bb4f04560811484&oe=5F1506E5',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 106232,
         'comments_count': 518,
         'timestamp': '2020-06-04T07:58:59+0000',
         'owner': {'id': '17841400193077467'},
         'permalink': 'https://www.instagram.com/p/CBAXIaAFEwv/',
         'id': '17867225362830120'}],
       'paging': {'cursors': {'after': 'QVFIUld1RXRSRWF5X185MmlsN3R5ekY3emMyX2xSWGZAHMlRGYzdzWnRKOGc4QUVkaWM4SzF0ZAmtaZAXdORXBFOW55N1NlZA0o3UU9xalB1NkhDM2VTNk1kWUhB'}}}},
     'id': '17841429540183149'}




```python
x[1]
```




    {'error': {'message': 'Invalid user id',
      'type': 'OAuthException',
      'code': 110,
      'error_subcode': 2207013,
      'is_transient': False,
      'error_user_title': 'Cannot find user',
      'error_user_msg': 'The user with username: shiromaniakalidal_ cannot be found.',
      'fbtrace_id': 'ANHRG5xvKbrpKcOihqlXGhV'}}




```python
x[2]
```




    {'business_discovery': {'biography': "The Indian National Congress is the world's largest democratic political organisation",
      'followers_count': 737046,
      'follows_count': 51,
      'id': '17841400292397696',
      'ig_id': 1132553746,
      'media_count': 2533,
      'name': 'Congress',
      'profile_picture_url': 'https://scontent.fdel1-1.fna.fbcdn.net/v/t51.2885-15/11254462_805774982872629_2023861758_a.jpg?_nc_cat=1&_nc_sid=86c713&_nc_ohc=1eRpneX3ZRYAX8AamgZ&_nc_ht=scontent.fdel1-1.fna&oh=6049b803ae9f7124486208b5c9c0bd53&oe=5F145ED5',
      'username': 'incindia',
      'website': 'http://www.inc.in/',
      'media': {'data': [{'caption': 'देश प्रधानमंत्री की बात पर विश्वास करे या रक्षामंत्री की? #BJP सरकार देश के सामने स्थिति स्पष्ट करने की जगह देश को गुमराह कर रही है। #IndiaDeservesToKnow',
         'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104170427_581378116107364_1338460485505880072_n.mp4?_nc_cat=104&vs=17857155890030532_2089826005&_nc_vs=HBksFQAYJEdMdUROUVprUEJla3doQUNBQWlRZVZpNEtwTVNia1lMQUFBRhUAAsgBABUAGCRHQVR3T2daeFA2RWE1ZkFBQUZCX3hYWkdCS3hhYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFoilqvCiv7g%2FFQIoAkMzLBdARi752yLQ5RgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=rSWZksHpYRQAX877H4T&_nc_ht=video.fdel1-2.fna&oh=e183c761ccb0c1fe4b62d6e9d8f31f5c&oe=5F17A2A5&_nc_rid=e3554a25f1',
         'media_type': 'VIDEO',
         'like_count': 1270,
         'comments_count': 28,
         'timestamp': '2020-06-22T09:12:09+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBu1xhQpKI4/',
         'id': '18104685928149130'},
        {'caption': 'This picture speaks louder than our current PM’s silence (Smt. #IndiraGandhi addressing Army jawans at #GalwanValley, Ladakh)\n.\n.\n.\n#Throwback\n#BnW',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104379239_140762534313755_2235825037415171921_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=xTLgALYAhbAAX9dHYtN&_nc_ht=scontent.cdninstagram.com&oh=65c84a824ceb9a57262b868579fb1a8f&oe=5F171C07',
         'media_type': 'IMAGE',
         'like_count': 9532,
         'comments_count': 95,
         'timestamp': '2020-06-22T06:26:41+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBui4DaJLlX/',
         'id': '18054200188245210'},
        {'caption': '“#Yoga includes non-violence, truthfulness, continence etc. It is an avoidance of malice and hatred.” - #JawaharlalNehru \n#InternationalYogaDay',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105978195_574792486808444_5964043191718885735_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=i7mb5u2Onk4AX9hCTRa&_nc_ht=scontent.cdninstagram.com&oh=9d8f5a5d5f077c9b980ab99cce19a6b3&oe=5F15BD16',
         'media_type': 'IMAGE',
         'like_count': 12628,
         'comments_count': 117,
         'timestamp': '2020-06-21T04:32:11+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBrw-kzpebW/',
         'id': '17845671716204236'},
        {'caption': "Even the PMO isn't confident about what the PM says - hence the contradiction in the statements. \n#ModiSurrendersToChina\n#PMModi",
         'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104421471_944966139282193_4849825040051136349_n.mp4?_nc_cat=100&vs=17924277823408978_3068789049&_nc_vs=HBksFQAYJEdGOVlPUVlSZ3c0VGNWc0RBRjNuQ3E4dENrNURia1lMQUFBRhUAAsgBABUAGCRHTW5ZUHdiX214LVZxb2tLQUl2dDVkQm9weTlPYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFqSYs52kgtc%2FFQIoAkMzLBdASK752yLQ5RgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=PHbHWRTM__8AX81_wbb&_nc_ht=video.fdel1-4.fna&oh=b074e6b75043b8208176ce6a1c61ed12&oe=5F169B79&_nc_rid=068de58f0b',
         'media_type': 'VIDEO',
         'like_count': 3746,
         'comments_count': 191,
         'timestamp': '2020-06-20T10:34:24+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBp1liMp3AV/',
         'id': '17856319280045951'},
        {'caption': 'To capitalise on opportunities in the midst of challenges, one needs to have a courageous and indomitable spirit. Leaders with such virtues have led our Nation to sail through many challenges of the past.\n\n#CongressKeVichaar',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104110830_715822572527746_3061748498572975866_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=pHSiY52MUXcAX_upLxR&_nc_ht=scontent.cdninstagram.com&oh=1ea8f64fe44c160d3b69b56df38264be&oe=5F1656F1',
         'media_type': 'IMAGE',
         'like_count': 8275,
         'comments_count': 53,
         'timestamp': '2020-06-20T05:18:51+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBpRhkqpZmx/',
         'id': '17903003914468339'},
        {'caption': 'इस सत्ता को चुभते हैं कुछ सवाल\nसवाल जो नाकामी पर प्रहार करे\nसवाल जो कपटी नीयत पर वार करे\nसवाल जो जनता के हितों का ख्याल करे\n\nये सवाल जारी रहेंगे...जनता के लिए',
         'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104341014_305967440410145_1099334899577466953_n.mp4?_nc_cat=105&vs=18145461115012617_1088922159&_nc_vs=HBksFQAYJEdCWWVPQVloTnBtWVJoWUJBRWt3Z1VKRW4wRVBia1lMQUFBRhUAAsgBABUAGCRHTVNjU1Fhc2w4enVfckFDQURsaHZSWVo3Q2doYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpKItLfrzLtAFQIoAkMzLBdATMRaHKwIMRgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=SBa7o57dfHYAX-rhdrP&_nc_ht=video.fdel1-4.fna&oh=46c9061b092fc9c0d2a9f1c86fdbe980&oe=5F158203&_nc_rid=81d2e1a6ff',
         'media_type': 'VIDEO',
         'like_count': 3330,
         'comments_count': 186,
         'timestamp': '2020-06-19T08:30:35+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBnClI1JFLI/',
         'id': '17877163132696478'},
        {'caption': 'Democracy is the expression of the will and wants of each and every citizen.\nrahulgandhi',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104019342_533121284234120_7863874374787307682_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=i8GyrqTz60wAX-NCXCq&_nc_ht=scontent.cdninstagram.com&oh=2424b2c000b5d3e63d210484ad52dc8a&oe=5F175E75',
         'media_type': 'IMAGE',
         'like_count': 23632,
         'comments_count': 432,
         'timestamp': '2020-06-19T03:46:43+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBmiL0opg8E/',
         'id': '17905494460469907'},
        {'caption': 'जो दुस्साहस चीन ने 53 साल में नहीं किया, उसकी आज इतनी हिम्मत कैसे हो गई?\n\n#TreacherousChina',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103673029_150948893177181_8536056608291036250_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=utR5zwsvPe0AX8fTRDF&_nc_ht=scontent.cdninstagram.com&oh=006d403cc0b1d4c487a8e2deed28f309&oe=5F168C8D',
         'media_type': 'IMAGE',
         'like_count': 9971,
         'comments_count': 348,
         'timestamp': '2020-06-18T12:52:03+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBk7zH2pEzG/',
         'id': '17904411436467397'},
        {'caption': 'Why were our soldiers unarmed amidst rising tensions at the border? \n#TreacherousChina',
         'media_url': 'https://video.fdel1-3.fna.fbcdn.net/v/t50.2886-16/103917597_268067667765368_3204911130508031090_n.mp4?_nc_cat=108&vs=17868882598827351_1061274239&_nc_vs=HBksFQAYJEdCMm9NUVo0NkJ4ZXp2TUFBSEowb0Y2eElYb3Nia1lMQUFBRhUAAsgBABUAGCRHRjYtT0FhcW0tTGNrZklBQUhiVnVFbHJfZk01YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFq72l9jt6b0%2FFQIoAkMzLBdASBm6XjU%2FfRgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=qGnk6AJtEf8AX8U5-nZ&_nc_ht=video.fdel1-3.fna&oh=baa8ad0a9e169a456630c5b47170523c&oe=5F1527AE&_nc_rid=f7be91fa0c',
         'media_type': 'VIDEO',
         'like_count': 3875,
         'comments_count': 70,
         'timestamp': '2020-06-18T10:48:25+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBktnFmJFK8/',
         'id': '17862680728930154'},
        {'caption': '20 of our brave hearts have been martyred at the hands of the Chinese Army. How dare #China intrude in our territory & kill our unarmed soldiers? \n#TreacherousChina\n\u2069',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103017304_203860697430564_3470571377145949547_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=woFl8POdDi4AX83d-pz&_nc_ht=scontent.cdninstagram.com&oh=7e1fdc3b8d2aba221d2ee7f816d040fc&oe=5F16EADC',
         'media_type': 'IMAGE',
         'like_count': 14096,
         'comments_count': 534,
         'timestamp': '2020-06-18T08:39:44+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBke7GVpIhV/',
         'id': '17842167746258136'},
        {'caption': "As India gets elected for its 8th term in #UNSC, it fills our hearts with pride that once again Indians will be showing the way to the world. This is a testament to India's long standing commitment towards humanitarian & democratic development in the world.\n#Congratulations",
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103912973_704697520331991_308671631639705721_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=SOwiY9B7Of8AX-UM7AP&_nc_ht=scontent.cdninstagram.com&oh=7aeab2651d055c27808dcdcf15ce804b&oe=5F1788BE',
         'media_type': 'IMAGE',
         'like_count': 8670,
         'comments_count': 75,
         'timestamp': '2020-06-18T07:39:34+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBkYCcrJPEJ/',
         'id': '17944627336360538'},
        {'caption': 'In this hour of crisis, let it be known that we as Indians have, are and will always stand together to uphold the sovereignty and integrity of our Nation.\n\n#CongressKeVichaar',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104038648_721832735309182_5848102739931651506_n.jpg?_nc_cat=101&_nc_sid=8ae9d6&_nc_ohc=xcBLoVzGMR8AX8Sk04D&_nc_ht=scontent.cdninstagram.com&oh=dd957d17ba4884ac6995908b2e176db7&oe=5F17D118',
         'media_type': 'IMAGE',
         'like_count': 5925,
         'comments_count': 81,
         'timestamp': '2020-06-18T04:53:21+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBkFA8VpYUw/',
         'id': '17877373282716304'},
        {'caption': 'हम तो विपक्ष है, आपने क्या किया?\n#PMDaroMatJawabDo',
         'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104079278_287809355963460_5751376487412483782_n.mp4?_nc_cat=104&vs=17895105091517602_1093396098&_nc_vs=HBksFQAYJEdLNGZOQVpFM0d6V3dnVUJBTVpHd1hWeC10QlBia1lMQUFBRhUAAsgBABUAGCRHSl9JTkFaM3BDWVJESzhBQUw4RjdzSUFyWWNDYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsTqwJ6a4Mk%2FFQIoAkMzLBdATR3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=BbGrPTp4GEYAX-fzmFd&_nc_ht=video.fdel1-2.fna&oh=8ca48a2713ce60ac85d5f563cc5ee072&oe=5F146086&_nc_rid=51b3dc0763',
         'media_type': 'VIDEO',
         'like_count': 3829,
         'comments_count': 147,
         'timestamp': '2020-06-17T09:04:56+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBh864upBX-/',
         'id': '18033535909265073'},
        {'caption': 'Where are these leaders when the nation needs them?\n\n#PMDaroMatJawabDo\n#PMModi\n#AmitShah\n#RajnathSingh',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103834579_138958684473650_3142810146740029834_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=ZZVChNbQlq0AX-zQhb3&_nc_ht=scontent.cdninstagram.com&oh=a75d217fefa016dcabcf815b0a2ef246&oe=5F146927',
         'media_type': 'IMAGE',
         'like_count': 9941,
         'comments_count': 226,
         'timestamp': '2020-06-17T08:44:35+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBh6rrIJg3I/',
         'id': '17900795782494345'},
        {'caption': 'A message for our brave martyrs from Shri rahulgandhi .\n\nदेश के वीर शहीदों को श्री rahulgandhi  का सलाम।',
         'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104468298_1246363379047041_4560505356078130524_n.mp4?_nc_cat=104&vs=18053319322246534_3604319899&_nc_vs=HBksFQAYJEdFb1BPZ2FCR25pV2oyMEVBRnlsVFhGMUswby1ia1lMQUFBRhUAAsgBABUAGCRHTUFGTHdaY3Nfd0UxamtJQU9uczhxX1RqUDlsYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFoyVzMG92ZFAFQIoAkMzLBdAO0RaHKwIMRgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=Kp2nuUIwkO8AX_crZ3B&_nc_ht=video.fdel1-2.fna&oh=15bfdc61d5a417b4401ed68d6bf843a1&oe=5F15FBE4&_nc_rid=d857af00f9',
         'media_type': 'VIDEO',
         'like_count': 12603,
         'comments_count': 306,
         'timestamp': '2020-06-17T05:59:04+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBhnj3Mpme6/',
         'id': '18149144914051751'},
        {'caption': 'These price increases are saddling our people with an additional burden of this enormous magnitude that is neither justified nor appropriate: Congress President Smt. #SoniaGandhi. \n#ModiStopLootingIndia',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103886495_263708551575751_5394649116907206411_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=AkK0d9Y5BYMAX9g-_kg&_nc_ht=scontent.cdninstagram.com&oh=f6e18174f8cfe19b12b66ed952b3ae14&oe=5F17990C',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 10334,
         'comments_count': 161,
         'timestamp': '2020-06-16T11:37:28+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBfprGwDEd-/',
         'id': '18122549761102846'},
        {'caption': 'Congress President Smt. #SoniaGandhi writes to the Prime Minister urging the govt to immediately roll back hikes on #FuelPrices & pass the benefit of low crude oil prices to the citizens.',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104017706_2488773548011810_1911958886266898770_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=4zJf4fXOUdYAX83Z5ai&_nc_ht=scontent.cdninstagram.com&oh=6d66b424724b40515ea43be7ee9ca1e9&oe=5F14FB8A',
         'media_type': 'CAROUSEL_ALBUM',
         'like_count': 7417,
         'comments_count': 92,
         'timestamp': '2020-06-16T04:40:19+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBe57ygjCSU/',
         'id': '17852758913089264'},
        {'caption': 'Tolerance has been one of the foundational principles of this Nation from time immemorial. To uphold this principle is the duty of each patriotic citizen.\n\n#CongressKeVichaar',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104167649_1157244254635556_6572278063820412279_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=YeM889avZLIAX9OcB90&_nc_ht=scontent.cdninstagram.com&oh=641e3ec90252b412dba213d0c1a753fd&oe=5F1774F2',
         'media_type': 'IMAGE',
         'like_count': 4305,
         'comments_count': 27,
         'timestamp': '2020-06-16T04:21:17+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBe3wayDKU7/',
         'id': '17871688270778317'},
        {'caption': "Each Indian's unwavering dedication to uphold the democratic values enshrined in our Constitution has allowed the India of our forefathers’ dreams to be a reality today. Any attempt to subvert these values will always be rejected.\n\n#CongressKeVichaar",
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103552497_943621902726943_5910493528061038295_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=eEY935g0tHwAX9e_AR8&_nc_ht=scontent.cdninstagram.com&oh=60bea97bbe9b31800b33d50a1a6d0a50&oe=5F154BE0',
         'media_type': 'IMAGE',
         'like_count': 5675,
         'comments_count': 15,
         'timestamp': '2020-06-15T04:34:42+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBcUfufJlFC/',
         'id': '17860886134927103'},
        {'caption': 'We are deeply shocked & saddened to hear about the untimely demise of the young & talented actor, #SushantSinghRajput. Our thoughts and prayers are with his family & friends in this time of grief.\n\nAs a nation we need to be more forthcoming about #MentalHealth. We need to talk about it, we need to create policies for it & we need to break the stigma around it. For the sake of our youth & our future, we must acknowledge the problem.',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103414571_274786153763653_2212772926284413363_n.jpg?_nc_cat=101&_nc_sid=8ae9d6&_nc_ohc=jX0SJcmEfXEAX_7olzF&_nc_ht=scontent.cdninstagram.com&oh=aafe3476cc867dfc64b66fc8bec10915&oe=5F152AEF',
         'media_type': 'IMAGE',
         'like_count': 31624,
         'comments_count': 262,
         'timestamp': '2020-06-14T12:36:17+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBam0KMpYbd/',
         'id': '17855599691047430'},
        {'caption': 'Some individuals attain fame due to their posturing, while others turn out to be valuable assets to the Nation because of their true devotion towards fellow citizens and their unrelenting dedication towards society.\n\n#CongressKeVichaar',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104161617_180247470109302_1314394772295479767_n.jpg?_nc_cat=106&_nc_sid=8ae9d6&_nc_ohc=4UZl0am5wHgAX-SmYd4&_nc_ht=scontent.cdninstagram.com&oh=8e4ac6303898e51fe197fcf071bb7e0d&oe=5F142E15',
         'media_type': 'IMAGE',
         'like_count': 7336,
         'comments_count': 51,
         'timestamp': '2020-06-14T04:32:33+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBZvdHfpwrp/',
         'id': '17844128282222131'},
        {'caption': "Rising #FuelPrices are hurting the common man and here's what the PM had to say about it.\n#YaadRakhna",
         'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/103716284_266938251314575_2593447021927970981_n.mp4?_nc_cat=104&vs=17910903625449107_2559638764&_nc_vs=HBksFQAYJEdMeVZMZ2FQaGFWbngtSUFBS1c0ejJWVHh2MGpia1lMQUFBRhUAAsgBABUAGCRHSi1xTEFhcENVNVltWU1GQUlqdG1kWWJCZFF6YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFqaU3M%2Fm99A%2FFQIoAkMzLBdATeaHKwIMShgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=bF6Jh5eTWrQAX854-_k&_nc_ht=video.fdel1-2.fna&oh=2788f030d97eac8a8d4fd25601b53961&oe=5F16273C&_nc_rid=6c01f6bbd0',
         'media_type': 'VIDEO',
         'like_count': 3825,
         'comments_count': 135,
         'timestamp': '2020-06-13T05:32:33+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBXRdlOpSGp/',
         'id': '17865319783844070'},
        {'caption': 'It is the prime duty of elected representatives to ensure that citizens are enabled and their demands met. When a deaf ear is turned on the citizens, democracy fails.\n\n#CongressKeVichaar',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103846199_2601239240189763_7309523997967586898_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=w6bpGGjCZG0AX_HfbAL&_nc_ht=scontent.cdninstagram.com&oh=516215677cbf67c206a049e05289adaa&oe=5F153747',
         'media_type': 'IMAGE',
         'like_count': 9437,
         'comments_count': 107,
         'timestamp': '2020-06-13T04:26:09+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBXJ7ddpfvG/',
         'id': '17852090282101150'},
        {'caption': "Here's your chance to become a warrior & highlight issues that trouble you. Send us your videos at SpeakupIndia@inc.in and not only will we highlight the best videos but also provide a chance to consistent campaigners to be the voice of INC as a media panelist.\n#SpeakUpWarriors",
         'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/102343403_282631239458142_7369783365241382702_n.mp4?_nc_cat=102&vs=17853839684071931_1617264121&_nc_vs=HBksFQAYJEdPdWlHUVplWGFFMkRRRUJBQzZueTRUc3VrWm1ia1lMQUFBRhUAAsgBABUAGCRHSWYySndhbnZIVXVQRE1CQUctd2pvdU85V1VzYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFva%2Fov%2Be%2FrY%2FFQIoAkMzLBdAR0ztkWhysBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=dNJdyoGPbXEAX9xKj-B&_nc_ht=video.fdel1-4.fna&oh=6be0b2d947b17ff5d132528522ed8d90&oe=5F144F94&_nc_rid=582444fb77',
         'media_type': 'VIDEO',
         'like_count': 2369,
         'comments_count': 29,
         'timestamp': '2020-06-12T14:00:32+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBVm03-pzEP/',
         'id': '17857925329990640'},
        {'caption': 'Indian American community is a real asset to both countries. This is a shared property. This is a good relationship: Shri rahulgandhi \n#RahulGandhiStandswithPeople',
         'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103853363_260794248479349_5177715456952293196_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=wBeq76RJkYcAX_YSSOA&_nc_ht=scontent.cdninstagram.com&oh=7f1b1218de372e472e7cc10cc9a9a7a9&oe=5F152D13',
         'media_type': 'IMAGE',
         'like_count': 7566,
         'comments_count': 112,
         'timestamp': '2020-06-12T11:12:14+0000',
         'owner': {'id': '17841400292397696'},
         'permalink': 'https://www.instagram.com/p/CBVTmu2JIXq/',
         'id': '17873803132730481'}],
       'paging': {'cursors': {'after': 'QVFIUlBXZAFc1NXpUeklibUplVHJ5bUN3YVYyNHVJSWVkRzhJOWNYcDR6blJSRndFZA0xJSFc1c08ta1NnRTAxVFZAPUnI0UjZAfTWg1a1RYcjVSUUp0TkFwamdR'}}},
      'recently_searched_hashtags': {'data': [{'id': '17843783248059507'}],
       'paging': {'cursors': {'before': 'QVFIUlFMYlJjckpJbnJ4amtpRlhad011LV9Gb3N6UjhYYUl5UGRXUUluTEZApSXpUVnc3cFBhTC12WXJTMUNMeXRDRzgwUGdWMmRUMVgtaXZATdFFzeTJvTlNn',
         'after': 'QVFIUlFMYlJjckpJbnJ4amtpRlhad011LV9Gb3N6UjhYYUl5UGRXUUluTEZApSXpUVnc3cFBhTC12WXJTMUNMeXRDRzgwUGdWMmRUMVgtaXZATdFFzeTJvTlNn'}}}},
     'id': '17841429540183149'}




```python

```


```python
x[0]['business_discovery']['biography']
```




    "Bharatiya Janata Party, founded in 1980, is World's largest political party. It currently leads the NDA, which is governing India.  #BJP  #India"




```python
 x[0]['business_discovery']['followers_count']
```




    3297381




```python
 x[0]['business_discovery']['follows_count']
```




    0




```python
 x[0]['business_discovery']['id']
```




    '17841400193077467'




```python
 x[0]['business_discovery']['media_count']
```




    3616




```python
 x[0]['business_discovery']['name']
```




    'BJP - Bharatiya Janata Party'




```python
 x[0]['business_discovery']['username']
```




    'bjp4india'




```python
 x[0]['business_discovery']['website']
```




    'https://www.bjp.org/membership'




```python
 x[0]['business_discovery']['media']
```




    {'data': [{'caption': 'लड़ाई जारी है लेकिन हौसले बुलंद है। जीतेंगे हम...',
       'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/105281340_196641258291866_7205467741881983526_n.mp4?_nc_cat=100&vs=17869559734829517_3228560770&_nc_vs=HBksFQAYJEdEeDNSZ2FhUWxrYzJMSUFBQ1ppYVN1ODl2NWpia1lMQUFBRhUAAsgBABUAGCRHTWphT1FiZzRlMjRVdzREQU1CUFp5T05uVVVJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpq8%2BtOikb4%2FFQIoAkMzLBdAPirAgxJumBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=AW8hg-F_MkIAX_4qXXe&_nc_ht=video.fdel1-4.fna&oh=177c7874d52c3b0a600436b702aa01b1&oe=5F1767E5&_nc_rid=0b3942b744',
       'media_type': 'VIDEO',
       'like_count': 16018,
       'comments_count': 66,
       'timestamp': '2020-06-22T05:48:45+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBuegpTAQRn/',
       'id': '17863465609926295'},
      {'caption': 'BJP National President Shri jpnaddaofficial performs yoga at his residence on #InternationalYogaDay today. #MyLifeMyYoga',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104053466_2317964778511660_5981624510555492019_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=JUPXH3DmOxMAX8y1O3N&_nc_ht=scontent.cdninstagram.com&oh=0a19fa241fd1c3d68c7856f2ca2b2a75&oe=5F15DE50',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 63768,
       'comments_count': 148,
       'timestamp': '2020-06-21T04:02:50+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBrtnoggN_k/',
       'id': '18059996809227284'},
      {'caption': 'कोरोना के संकटकाल में भी टेक्नोलॉजी के माध्यम से देश के जन-जन तक पहुंच रही है भारतीय जनता पार्टी। आज भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial के राजस्थान जनसंवाद रैली में संबोधन को सुनते आमजन।',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105414284_265420581539185_4630206849005528189_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=Hxn-B9z-d0EAX_IB2AH&_nc_ht=scontent.cdninstagram.com&oh=e719ea92eab6f1b1961397dfb105502e&oe=5F157E9D',
       'media_type': 'IMAGE',
       'like_count': 34851,
       'comments_count': 118,
       'timestamp': '2020-06-20T13:37:31+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBqKlz4ASym/',
       'id': '18091724080175849'},
      {'caption': 'राहुल गांधी, सुनिए हमारे वीर जवान के वीर पिता की भावनाओं को और बंद कीजिए उनके नाम पर निकृष्ट राजनीति। #india #bjp #china',
       'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104735923_1188447364835330_3114894258955085295_n.mp4?_nc_cat=100&vs=17877093337693291_566229461&_nc_vs=HBksFQAYJEdMTWtQZ1lDNkFQMzRqZ0VBTy1sNnpuVFV6b3Jia1lMQUFBRhUAAsgBABUAGCRHR0NaT1FhUWRuQ1BreVlCQU1XdXdwd1V0UmtJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFtaZosnkx8E%2FFQIoAkMzLBdAQEiTdLxqfxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=0REsp84tcW8AX9F6h3j&_nc_ht=video.fdel1-4.fna&oh=1159a1ac7de66f95cd74591ff9055f93&oe=5F1764F9&_nc_rid=7c1a08f482',
       'media_type': 'VIDEO',
       'like_count': 19614,
       'comments_count': 179,
       'timestamp': '2020-06-20T05:01:07+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBpPeZxAd5z/',
       'id': '17887502845575049'},
      {'caption': 'भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial 20 जून 2020 को दोपहर 12.30 बजे वीडियो कॉन्फ़्रेंसिंग के माध्यम से राजस्थान जनसंवाद रैली को संबोधित करेंगे। BJP4Rajasthan',
       'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104265490_292049665296242_423465061768528093_n.mp4?_nc_cat=107&vs=17857036247024519_3284310992&_nc_vs=HBksFQAYJEdCTDNOZ1p5aDQ0Y25na0JBTjJBZ09VNmNfQUZia1lMQUFBRhUAAsgBABUAGCRHSDZYT0FZS0hFWklvLUVBQUc5Y3c3ZmJrMlpvYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFo7X66enuLg%2FFQIoAkMzLBdANV3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=saabCtPvwukAX83CWTS&_nc_ht=video.fdel1-2.fna&oh=4f35aada4816b6b365a2b0446cc5a66f&oe=5F15A1C1&_nc_rid=4ea34c4e61',
       'media_type': 'VIDEO',
       'like_count': 16005,
       'comments_count': 44,
       'timestamp': '2020-06-19T17:11:30+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBn-QQ9FWKa/',
       'id': '18152066587031624'},
      {'caption': 'PM narendramodi holds All Party Meeting to discuss situation in India-China border areas\n.\n.\n20 of our brave soldiers made the supreme sacrifice in Ladakh but also taught a lesson to those who dared to look towards our motherland. Neither is anyone inside our territory nor is any of our post captured; India wants peace and friendship, but upholding sovereignty is foremost: PM narendramodi',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104101998_579856346007751_1019788892395299541_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=tacps046vWcAX8u0QB2&_nc_ht=scontent.cdninstagram.com&oh=ec16af88a1bad743b7948aea877bc480&oe=5F17339C',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 88308,
       'comments_count': 319,
       'timestamp': '2020-06-19T16:36:37+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBn6Sz0gg-V/',
       'id': '17888904943571172'},
      {'caption': "Modi govt's huge relief to Delhiites. \nOn instructions of Home Minister Shri amitshahofficial, the cost of treatment of COVID-19 patients in private hospitals of Delhi has been reduced by about two-thirds.\n\nPPE kits and medicines are also included in the new rates.",
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105020102_191367085579754_6719776562378654198_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=cUJkZK9oWeUAX8bCrdX&_nc_ht=scontent.cdninstagram.com&oh=9c5485f63f3e7558279e69169bcc28b2&oe=5F16869C',
       'media_type': 'IMAGE',
       'like_count': 28970,
       'comments_count': 269,
       'timestamp': '2020-06-19T13:26:29+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBnkiO9gXcK/',
       'id': '17875144507732012'},
      {'caption': 'BJP has decided to postpone all its political programmes including virtual rallies for next 2 days.',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104103516_103667658011266_3962349400865496458_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=SrzDIB3ShaYAX9rdr23&_nc_ht=scontent.cdninstagram.com&oh=3370eb484c2794f990b23eb2f3b8b697&oe=5F1733FD',
       'media_type': 'IMAGE',
       'like_count': 23698,
       'comments_count': 145,
       'timestamp': '2020-06-18T06:09:47+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBkNw3AAJ0A/',
       'id': '18121635580113888'},
      {'caption': '1857 के प्रथम स्वतंत्रता संग्राम में अंग्रेज़ी शासन के विरुद्ध अग्रिम भूमिका निभाकर अपने प्राणों की आहुति देने वाली महान वीरांगना रानी लक्ष्मीबाई की पुण्यतिथि पर कोटि-कोटि नमन।',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103661980_566983254001582_7367512126551480632_n.jpg?_nc_cat=108&_nc_sid=8ae9d6&_nc_ohc=C5KmytflgHYAX-jQdzx&_nc_ht=scontent.cdninstagram.com&oh=cb83d40338ed9cd684123c8b47109659&oe=5F16ECD6',
       'media_type': 'IMAGE',
       'like_count': 37857,
       'comments_count': 231,
       'timestamp': '2020-06-18T04:33:14+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBkCtskA-wB/',
       'id': '17874635890734764'},
      {'caption': 'भारत शांति चाहता है, लेकिन भारत उकसाने पर हर हाल में यथोचित जवाब देने में सक्षम है। हमारे दिवंगत शहीद वीर जवानों के विषय में देश को इस बात में गर्व होगा कि वे मारते-मारते मरे हैं: प्रधानमंत्री श्री narendramodi',
       'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104485235_2728637797458196_1083507323252640862_n.mp4?_nc_cat=102&vs=17876598496707417_2072603921&_nc_vs=HBksFQAYJEdITlJPZ1lVWWFOX3JyRUpBRjRNQW5vclpBa1Bia1lMQUFBRhUAAsgBABUAGCRHS2YwTmdZQ0lIVjRYQUVKQUFrWHVCYl85Ynd3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFrLqvqv9qsE%2FFQIoAkMzLBdARfeNT987ZBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=JTZii5Y9M0oAX-V7vRo&_nc_ht=video.fdel1-4.fna&oh=8183b16ee1a4786bb958993128c4bfdc&oe=5F15687B&_nc_rid=b66e01f968',
       'media_type': 'VIDEO',
       'like_count': 32520,
       'comments_count': 454,
       'timestamp': '2020-06-17T15:54:43+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBir3VWARag/',
       'id': '18110380408137861'},
      {'caption': "Stay tuned for BJP National President Shri jpnaddaofficial's 'Kerala Jan Samvad Rally' on 16 June 2020.\n\nWatch the live webcast of the virtual rally on all social media platforms of BJP. #BJPJanSamvad",
       'media_url': 'https://video.fdel1-1.fna.fbcdn.net/v/t50.2886-16/103700248_282523916206191_4692889505717351644_n.mp4?_nc_cat=110&vs=17861586256940324_2588048645&_nc_vs=HBksFQAYJEdCaFhMZ1p2Z0tvNTlBQUJBTnowY0RZa2ZpQkJia1lMQUFBRhUAAsgBABUAGCRHQUxOSmdaYUF2SEZBdTRBQUtCOUE1MElmcFF0YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsjOgsyTwbo%2FFQIoAkMzLBdANTvnbItDlhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=66F1LprSIjUAX883oTc&_nc_ht=video.fdel1-1.fna&oh=db5c5e29bd5290dc448e599893fd27cd&oe=5F165617&_nc_rid=9e8615f55b',
       'media_type': 'VIDEO',
       'like_count': 14411,
       'comments_count': 66,
       'timestamp': '2020-06-15T15:43:51+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBdhBXRA31s/',
       'id': '17845962995194100'},
      {'caption': 'Union Home Minister amitshahofficial’s visit to Delhi government run LNJP hospital, which was in news recently for poor condition of COVID patients, will surely motivate the administration to do better and also comes as a huge relief to the people of Delhi, who have been struggling... #corona #covid19 #india #delhi #bjp',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103423255_148163790127729_5963460060476933287_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=sv5ab-9triYAX8zr8aq&_nc_ht=scontent.cdninstagram.com&oh=3a4d5605332fae1a78efc533215cba3e&oe=5F16366C',
       'media_type': 'IMAGE',
       'like_count': 42417,
       'comments_count': 158,
       'timestamp': '2020-06-15T13:57:30+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBdU554gNKp/',
       'id': '17948760484349375'},
      {'caption': 'You donated and ventilators are here! #PMCARES #thankyou',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82512168_107360344267408_194752731509630725_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=Cd-534nZzWAAX9rQN0E&_nc_ht=scontent.cdninstagram.com&oh=93b694f11ee3985b6d5417f7e1bf67bb&oe=5F174E7D',
       'media_type': 'IMAGE',
       'like_count': 82829,
       'comments_count': 842,
       'timestamp': '2020-06-14T18:12:04+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBbNPcTgnAg/',
       'id': '17892137323548652'},
      {'caption': 'HM Shri amitshahofficial chairs meeting to review COVID-19 situation in Delhi. • Modi govt to immediately provide 500 converted rail coaches to the Delhi govt, adding 8,000 beds for COVID-19 patients. • Testing to double in 2 days and treble in 6 days. #corona #covid19 #delhi #india #bjp',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104218735_113841486841448_3291412899190214212_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=ta2T0QsVNBcAX-S4DpM&_nc_ht=scontent.cdninstagram.com&oh=40bbc553621b2432464f7e346925cf33&oe=5F1518DD',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 40060,
       'comments_count': 108,
       'timestamp': '2020-06-14T17:59:27+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBbLzDvgV9E/',
       'id': '18038595586259710'},
      {'caption': "'Sabka Saath' \nSabka Vikas,\nSabka Vishwas,\nin action and spirit. #SamajikSamarasta",
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103509872_113653220191611_5932068315779119246_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=yYeyVsoBTFQAX_YuPeb&_nc_ht=scontent.cdninstagram.com&oh=3479ee1c0360c05739a61658f78c281b&oe=5F14B5BC',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 19663,
       'comments_count': 212,
       'timestamp': '2020-06-13T06:05:05+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBXVQC2gJCJ/',
       'id': '17861022121945904'},
      {'caption': 'Modi Government is providing better lifestyle, security and rights to minorities, children and the persecuted. \nBy means of fair justice and equality, it is building a New India that gives a level playing field to everyone. #minorities #security #children #SamajikSamarasta',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82213218_3605854582775422_2878777493708641606_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=jiJYDo8Jyd8AX8_mUxq&_nc_ht=scontent.cdninstagram.com&oh=d83ef5bcbc7821c9b98e46780401aab9&oe=5F164B53',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 18600,
       'comments_count': 105,
       'timestamp': '2020-06-13T05:30:28+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBXRScAAVZJ/',
       'id': '17856215609027235'},
      {'caption': 'देश की स्वतंत्रता के लिए अपने प्राणों की आहुति देने वाले अमर शहीद पं. राम प्रसाद बिस्मिल जी की जयंती पर शत्-शत् नमन।',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103365587_565758700709634_7405577148654248981_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=EoKTsl_H-7wAX9oVLA6&_nc_ht=scontent.cdninstagram.com&oh=e75afe2dafb331840778b4c928473230&oe=5F14D832',
       'media_type': 'IMAGE',
       'like_count': 25150,
       'comments_count': 180,
       'timestamp': '2020-06-11T06:29:28+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBSOc4hgiSw/',
       'id': '17997905677288721'},
      {'caption': 'Development of India’s Gateway to the East, the Northeast, has been one of the major revolutions brought by the Modi government.\n\nA look at several such measures and work done... #newnortheast',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103185094_253745506071244_8212898175183513492_n.jpg?_nc_cat=102&_nc_sid=8ae9d6&_nc_ohc=7rb2QQm7ocAAX-Qs-LK&_nc_ht=scontent.cdninstagram.com&oh=2e8fbf1bc10abe71169ef6826606f5a2&oe=5F147696',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 19302,
       'comments_count': 77,
       'timestamp': '2020-06-11T03:24:27+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBR5RwBgs3V/',
       'id': '18104000863182004'},
      {'caption': "Modi government has always taken special care of India's flora and fauna. This has resulted in the rise in population of the majestic Asiatic Lion, living in Gujarat’s Gir Forest, by almost 29%. Geographically, the distribution area rose by 36%. India is the home to Asiatic Lion, and kudos to the hardwork of the people who keep their lives safe.",
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102879900_744323092985160_6731549785779784998_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=968gkWmvZ9UAX_cTSIw&_nc_ht=scontent.cdninstagram.com&oh=2ec6b3dc3295269c5bbbd0204c6fb909&oe=5F14303E',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 55072,
       'comments_count': 322,
       'timestamp': '2020-06-10T14:23:36+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBQf6pqgplm/',
       'id': '17860584838943065'},
      {'caption': 'People from across the world tuned in to watch the virtual rally of Shri amitshahofficial\n#BanglarJanasamabesh',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102722209_2605887319654066_5107787965378137175_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=IiQil-MWR6YAX_KIJV1&_nc_ht=scontent.cdninstagram.com&oh=d3068f273e58748b6836679eaf90441d&oe=5F17C9E1',
       'media_type': 'IMAGE',
       'like_count': 57826,
       'comments_count': 388,
       'timestamp': '2020-06-09T09:55:46+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBNceHcgl6R/',
       'id': '17874951385728643'},
      {'caption': 'महान स्वतंत्रता सेनानी एवं जननायक भगवान बिरसा मुंडा जी की पुण्यतिथि पर विनम्र श्रद्धांजलि।',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103280597_3057825094254797_3884304578204713535_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=jqN4UkGWW_kAX8XLrPR&_nc_ht=scontent.cdninstagram.com&oh=e1e1ed4e64c49abc7623e75857390a13&oe=5F168630',
       'media_type': 'IMAGE',
       'like_count': 35190,
       'comments_count': 170,
       'timestamp': '2020-06-09T06:33:14+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBNFSrDgIIR/',
       'id': '17843311712229115'},
      {'caption': 'Odisha #BJPJanSamvad in pictures...',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102688611_111240973800675_3675080288425326366_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=gH6s-vPJf78AX-tKsF5&_nc_ht=scontent.cdninstagram.com&oh=8d4d7af55f801525aaabdd2752c0b813&oe=5F18153E',
       'media_type': 'IMAGE',
       'like_count': 33874,
       'comments_count': 203,
       'timestamp': '2020-06-08T17:25:45+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBLrK_Zgc69/',
       'id': '18056941192242702'},
      {'caption': 'बिहार के जन-जन ने सुनी #बिहार_जनसंवाद रैली...',
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102705657_274392950281791_8017325389862027533_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=gucFSfG15pgAX-wrFMW&_nc_ht=scontent.cdninstagram.com&oh=a9e66393c568ae5386b05ca989e76020&oe=5F17EEB4',
       'media_type': 'IMAGE',
       'like_count': 44691,
       'comments_count': 349,
       'timestamp': '2020-06-07T18:23:54+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBJNCFCABHg/',
       'id': '17850850097105388'},
      {'caption': 'BJP National President Shri jpnaddaofficial plants a sapling on #WorldEnvironmentDay.',
       'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/103183755_832763770583557_8700377016758320263_n.mp4?_nc_cat=107&vs=17948495521346275_1104447547&_nc_vs=HBksFQAYJEdJdDFKZ1lGT3Jyc1pQVUNBSWM4MnRmTThyMTRia1lMQUFBRhUAAsgBABUAGCRHTzd5SWdibE9fNTlKVEFMQVBqaFgzQ1lUbEV3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsbYi6P4g%2BI%2FFQIoAkMzLBdAOAi0OVgQYhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=pqswPNjUho8AX8gpj3q&_nc_ht=video.fdel1-2.fna&oh=6301d7e55708b8a2264ab6cac9877cc3&oe=5F1740C6&_nc_rid=f9f39f2727',
       'media_type': 'VIDEO',
       'like_count': 26635,
       'comments_count': 211,
       'timestamp': '2020-06-05T08:22:51+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBC-o0PA69a/',
       'id': '18118938049113698'},
      {'caption': "I wish I could be there for what has become the famous 'Modi hug' & have my share of samosas. Next time, it will have to be the Gujarati Khichdi. I will try that in the kitchen before next time we meet in person: Australian PM scottmorrisonmp\n.\n.\nPM narendramodi and Australian PM scottmorrisonmp address 1st virtual India-Australia summit. #india #modihug #bjp #australia",
       'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/101815786_689123381939267_7050305340797946967_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=KqRBMzlminEAX9ZME2p&_nc_ht=scontent.cdninstagram.com&oh=782d2ca5255b711b8bb4f04560811484&oe=5F1506E5',
       'media_type': 'CAROUSEL_ALBUM',
       'like_count': 106232,
       'comments_count': 518,
       'timestamp': '2020-06-04T07:58:59+0000',
       'owner': {'id': '17841400193077467'},
       'permalink': 'https://www.instagram.com/p/CBAXIaAFEwv/',
       'id': '17867225362830120'}],
     'paging': {'cursors': {'after': 'QVFIUld1RXRSRWF5X185MmlsN3R5ekY3emMyX2xSWGZAHMlRGYzdzWnRKOGc4QUVkaWM4SzF0ZAmtaZAXdORXBFOW55N1NlZA0o3UU9xalB1NkhDM2VTNk1kWUhB'}}}




```python
 x[0]['business_discovery']['media']['data']
```




    [{'caption': 'लड़ाई जारी है लेकिन हौसले बुलंद है। जीतेंगे हम...',
      'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/105281340_196641258291866_7205467741881983526_n.mp4?_nc_cat=100&vs=17869559734829517_3228560770&_nc_vs=HBksFQAYJEdEeDNSZ2FhUWxrYzJMSUFBQ1ppYVN1ODl2NWpia1lMQUFBRhUAAsgBABUAGCRHTWphT1FiZzRlMjRVdzREQU1CUFp5T05uVVVJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpq8%2BtOikb4%2FFQIoAkMzLBdAPirAgxJumBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=AW8hg-F_MkIAX_4qXXe&_nc_ht=video.fdel1-4.fna&oh=177c7874d52c3b0a600436b702aa01b1&oe=5F1767E5&_nc_rid=0b3942b744',
      'media_type': 'VIDEO',
      'like_count': 16018,
      'comments_count': 66,
      'timestamp': '2020-06-22T05:48:45+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBuegpTAQRn/',
      'id': '17863465609926295'},
     {'caption': 'BJP National President Shri jpnaddaofficial performs yoga at his residence on #InternationalYogaDay today. #MyLifeMyYoga',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104053466_2317964778511660_5981624510555492019_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=JUPXH3DmOxMAX8y1O3N&_nc_ht=scontent.cdninstagram.com&oh=0a19fa241fd1c3d68c7856f2ca2b2a75&oe=5F15DE50',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 63768,
      'comments_count': 148,
      'timestamp': '2020-06-21T04:02:50+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBrtnoggN_k/',
      'id': '18059996809227284'},
     {'caption': 'कोरोना के संकटकाल में भी टेक्नोलॉजी के माध्यम से देश के जन-जन तक पहुंच रही है भारतीय जनता पार्टी। आज भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial के राजस्थान जनसंवाद रैली में संबोधन को सुनते आमजन।',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105414284_265420581539185_4630206849005528189_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=Hxn-B9z-d0EAX_IB2AH&_nc_ht=scontent.cdninstagram.com&oh=e719ea92eab6f1b1961397dfb105502e&oe=5F157E9D',
      'media_type': 'IMAGE',
      'like_count': 34851,
      'comments_count': 118,
      'timestamp': '2020-06-20T13:37:31+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBqKlz4ASym/',
      'id': '18091724080175849'},
     {'caption': 'राहुल गांधी, सुनिए हमारे वीर जवान के वीर पिता की भावनाओं को और बंद कीजिए उनके नाम पर निकृष्ट राजनीति। #india #bjp #china',
      'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104735923_1188447364835330_3114894258955085295_n.mp4?_nc_cat=100&vs=17877093337693291_566229461&_nc_vs=HBksFQAYJEdMTWtQZ1lDNkFQMzRqZ0VBTy1sNnpuVFV6b3Jia1lMQUFBRhUAAsgBABUAGCRHR0NaT1FhUWRuQ1BreVlCQU1XdXdwd1V0UmtJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFtaZosnkx8E%2FFQIoAkMzLBdAQEiTdLxqfxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=0REsp84tcW8AX9F6h3j&_nc_ht=video.fdel1-4.fna&oh=1159a1ac7de66f95cd74591ff9055f93&oe=5F1764F9&_nc_rid=7c1a08f482',
      'media_type': 'VIDEO',
      'like_count': 19614,
      'comments_count': 179,
      'timestamp': '2020-06-20T05:01:07+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBpPeZxAd5z/',
      'id': '17887502845575049'},
     {'caption': 'भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial 20 जून 2020 को दोपहर 12.30 बजे वीडियो कॉन्फ़्रेंसिंग के माध्यम से राजस्थान जनसंवाद रैली को संबोधित करेंगे। BJP4Rajasthan',
      'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104265490_292049665296242_423465061768528093_n.mp4?_nc_cat=107&vs=17857036247024519_3284310992&_nc_vs=HBksFQAYJEdCTDNOZ1p5aDQ0Y25na0JBTjJBZ09VNmNfQUZia1lMQUFBRhUAAsgBABUAGCRHSDZYT0FZS0hFWklvLUVBQUc5Y3c3ZmJrMlpvYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFo7X66enuLg%2FFQIoAkMzLBdANV3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=saabCtPvwukAX83CWTS&_nc_ht=video.fdel1-2.fna&oh=4f35aada4816b6b365a2b0446cc5a66f&oe=5F15A1C1&_nc_rid=4ea34c4e61',
      'media_type': 'VIDEO',
      'like_count': 16005,
      'comments_count': 44,
      'timestamp': '2020-06-19T17:11:30+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBn-QQ9FWKa/',
      'id': '18152066587031624'},
     {'caption': 'PM narendramodi holds All Party Meeting to discuss situation in India-China border areas\n.\n.\n20 of our brave soldiers made the supreme sacrifice in Ladakh but also taught a lesson to those who dared to look towards our motherland. Neither is anyone inside our territory nor is any of our post captured; India wants peace and friendship, but upholding sovereignty is foremost: PM narendramodi',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104101998_579856346007751_1019788892395299541_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=tacps046vWcAX8u0QB2&_nc_ht=scontent.cdninstagram.com&oh=ec16af88a1bad743b7948aea877bc480&oe=5F17339C',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 88308,
      'comments_count': 319,
      'timestamp': '2020-06-19T16:36:37+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBn6Sz0gg-V/',
      'id': '17888904943571172'},
     {'caption': "Modi govt's huge relief to Delhiites. \nOn instructions of Home Minister Shri amitshahofficial, the cost of treatment of COVID-19 patients in private hospitals of Delhi has been reduced by about two-thirds.\n\nPPE kits and medicines are also included in the new rates.",
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105020102_191367085579754_6719776562378654198_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=cUJkZK9oWeUAX8bCrdX&_nc_ht=scontent.cdninstagram.com&oh=9c5485f63f3e7558279e69169bcc28b2&oe=5F16869C',
      'media_type': 'IMAGE',
      'like_count': 28970,
      'comments_count': 269,
      'timestamp': '2020-06-19T13:26:29+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBnkiO9gXcK/',
      'id': '17875144507732012'},
     {'caption': 'BJP has decided to postpone all its political programmes including virtual rallies for next 2 days.',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104103516_103667658011266_3962349400865496458_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=SrzDIB3ShaYAX9rdr23&_nc_ht=scontent.cdninstagram.com&oh=3370eb484c2794f990b23eb2f3b8b697&oe=5F1733FD',
      'media_type': 'IMAGE',
      'like_count': 23698,
      'comments_count': 145,
      'timestamp': '2020-06-18T06:09:47+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBkNw3AAJ0A/',
      'id': '18121635580113888'},
     {'caption': '1857 के प्रथम स्वतंत्रता संग्राम में अंग्रेज़ी शासन के विरुद्ध अग्रिम भूमिका निभाकर अपने प्राणों की आहुति देने वाली महान वीरांगना रानी लक्ष्मीबाई की पुण्यतिथि पर कोटि-कोटि नमन।',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103661980_566983254001582_7367512126551480632_n.jpg?_nc_cat=108&_nc_sid=8ae9d6&_nc_ohc=C5KmytflgHYAX-jQdzx&_nc_ht=scontent.cdninstagram.com&oh=cb83d40338ed9cd684123c8b47109659&oe=5F16ECD6',
      'media_type': 'IMAGE',
      'like_count': 37857,
      'comments_count': 231,
      'timestamp': '2020-06-18T04:33:14+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBkCtskA-wB/',
      'id': '17874635890734764'},
     {'caption': 'भारत शांति चाहता है, लेकिन भारत उकसाने पर हर हाल में यथोचित जवाब देने में सक्षम है। हमारे दिवंगत शहीद वीर जवानों के विषय में देश को इस बात में गर्व होगा कि वे मारते-मारते मरे हैं: प्रधानमंत्री श्री narendramodi',
      'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104485235_2728637797458196_1083507323252640862_n.mp4?_nc_cat=102&vs=17876598496707417_2072603921&_nc_vs=HBksFQAYJEdITlJPZ1lVWWFOX3JyRUpBRjRNQW5vclpBa1Bia1lMQUFBRhUAAsgBABUAGCRHS2YwTmdZQ0lIVjRYQUVKQUFrWHVCYl85Ynd3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFrLqvqv9qsE%2FFQIoAkMzLBdARfeNT987ZBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=JTZii5Y9M0oAX-V7vRo&_nc_ht=video.fdel1-4.fna&oh=8183b16ee1a4786bb958993128c4bfdc&oe=5F15687B&_nc_rid=b66e01f968',
      'media_type': 'VIDEO',
      'like_count': 32520,
      'comments_count': 454,
      'timestamp': '2020-06-17T15:54:43+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBir3VWARag/',
      'id': '18110380408137861'},
     {'caption': "Stay tuned for BJP National President Shri jpnaddaofficial's 'Kerala Jan Samvad Rally' on 16 June 2020.\n\nWatch the live webcast of the virtual rally on all social media platforms of BJP. #BJPJanSamvad",
      'media_url': 'https://video.fdel1-1.fna.fbcdn.net/v/t50.2886-16/103700248_282523916206191_4692889505717351644_n.mp4?_nc_cat=110&vs=17861586256940324_2588048645&_nc_vs=HBksFQAYJEdCaFhMZ1p2Z0tvNTlBQUJBTnowY0RZa2ZpQkJia1lMQUFBRhUAAsgBABUAGCRHQUxOSmdaYUF2SEZBdTRBQUtCOUE1MElmcFF0YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsjOgsyTwbo%2FFQIoAkMzLBdANTvnbItDlhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=66F1LprSIjUAX883oTc&_nc_ht=video.fdel1-1.fna&oh=db5c5e29bd5290dc448e599893fd27cd&oe=5F165617&_nc_rid=9e8615f55b',
      'media_type': 'VIDEO',
      'like_count': 14411,
      'comments_count': 66,
      'timestamp': '2020-06-15T15:43:51+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBdhBXRA31s/',
      'id': '17845962995194100'},
     {'caption': 'Union Home Minister amitshahofficial’s visit to Delhi government run LNJP hospital, which was in news recently for poor condition of COVID patients, will surely motivate the administration to do better and also comes as a huge relief to the people of Delhi, who have been struggling... #corona #covid19 #india #delhi #bjp',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103423255_148163790127729_5963460060476933287_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=sv5ab-9triYAX8zr8aq&_nc_ht=scontent.cdninstagram.com&oh=3a4d5605332fae1a78efc533215cba3e&oe=5F16366C',
      'media_type': 'IMAGE',
      'like_count': 42417,
      'comments_count': 158,
      'timestamp': '2020-06-15T13:57:30+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBdU554gNKp/',
      'id': '17948760484349375'},
     {'caption': 'You donated and ventilators are here! #PMCARES #thankyou',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82512168_107360344267408_194752731509630725_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=Cd-534nZzWAAX9rQN0E&_nc_ht=scontent.cdninstagram.com&oh=93b694f11ee3985b6d5417f7e1bf67bb&oe=5F174E7D',
      'media_type': 'IMAGE',
      'like_count': 82829,
      'comments_count': 842,
      'timestamp': '2020-06-14T18:12:04+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBbNPcTgnAg/',
      'id': '17892137323548652'},
     {'caption': 'HM Shri amitshahofficial chairs meeting to review COVID-19 situation in Delhi. • Modi govt to immediately provide 500 converted rail coaches to the Delhi govt, adding 8,000 beds for COVID-19 patients. • Testing to double in 2 days and treble in 6 days. #corona #covid19 #delhi #india #bjp',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104218735_113841486841448_3291412899190214212_n.jpg?_nc_cat=109&_nc_sid=8ae9d6&_nc_ohc=ta2T0QsVNBcAX-S4DpM&_nc_ht=scontent.cdninstagram.com&oh=40bbc553621b2432464f7e346925cf33&oe=5F1518DD',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 40060,
      'comments_count': 108,
      'timestamp': '2020-06-14T17:59:27+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBbLzDvgV9E/',
      'id': '18038595586259710'},
     {'caption': "'Sabka Saath' \nSabka Vikas,\nSabka Vishwas,\nin action and spirit. #SamajikSamarasta",
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103509872_113653220191611_5932068315779119246_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=yYeyVsoBTFQAX_YuPeb&_nc_ht=scontent.cdninstagram.com&oh=3479ee1c0360c05739a61658f78c281b&oe=5F14B5BC',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 19663,
      'comments_count': 212,
      'timestamp': '2020-06-13T06:05:05+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBXVQC2gJCJ/',
      'id': '17861022121945904'},
     {'caption': 'Modi Government is providing better lifestyle, security and rights to minorities, children and the persecuted. \nBy means of fair justice and equality, it is building a New India that gives a level playing field to everyone. #minorities #security #children #SamajikSamarasta',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/82213218_3605854582775422_2878777493708641606_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=jiJYDo8Jyd8AX8_mUxq&_nc_ht=scontent.cdninstagram.com&oh=d83ef5bcbc7821c9b98e46780401aab9&oe=5F164B53',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 18600,
      'comments_count': 105,
      'timestamp': '2020-06-13T05:30:28+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBXRScAAVZJ/',
      'id': '17856215609027235'},
     {'caption': 'देश की स्वतंत्रता के लिए अपने प्राणों की आहुति देने वाले अमर शहीद पं. राम प्रसाद बिस्मिल जी की जयंती पर शत्-शत् नमन।',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103365587_565758700709634_7405577148654248981_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=EoKTsl_H-7wAX9oVLA6&_nc_ht=scontent.cdninstagram.com&oh=e75afe2dafb331840778b4c928473230&oe=5F14D832',
      'media_type': 'IMAGE',
      'like_count': 25150,
      'comments_count': 180,
      'timestamp': '2020-06-11T06:29:28+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBSOc4hgiSw/',
      'id': '17997905677288721'},
     {'caption': 'Development of India’s Gateway to the East, the Northeast, has been one of the major revolutions brought by the Modi government.\n\nA look at several such measures and work done... #newnortheast',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103185094_253745506071244_8212898175183513492_n.jpg?_nc_cat=102&_nc_sid=8ae9d6&_nc_ohc=7rb2QQm7ocAAX-Qs-LK&_nc_ht=scontent.cdninstagram.com&oh=2e8fbf1bc10abe71169ef6826606f5a2&oe=5F147696',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 19302,
      'comments_count': 77,
      'timestamp': '2020-06-11T03:24:27+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBR5RwBgs3V/',
      'id': '18104000863182004'},
     {'caption': "Modi government has always taken special care of India's flora and fauna. This has resulted in the rise in population of the majestic Asiatic Lion, living in Gujarat’s Gir Forest, by almost 29%. Geographically, the distribution area rose by 36%. India is the home to Asiatic Lion, and kudos to the hardwork of the people who keep their lives safe.",
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102879900_744323092985160_6731549785779784998_n.jpg?_nc_cat=105&_nc_sid=8ae9d6&_nc_ohc=968gkWmvZ9UAX_cTSIw&_nc_ht=scontent.cdninstagram.com&oh=2ec6b3dc3295269c5bbbd0204c6fb909&oe=5F14303E',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 55072,
      'comments_count': 322,
      'timestamp': '2020-06-10T14:23:36+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBQf6pqgplm/',
      'id': '17860584838943065'},
     {'caption': 'People from across the world tuned in to watch the virtual rally of Shri amitshahofficial\n#BanglarJanasamabesh',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102722209_2605887319654066_5107787965378137175_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=IiQil-MWR6YAX_KIJV1&_nc_ht=scontent.cdninstagram.com&oh=d3068f273e58748b6836679eaf90441d&oe=5F17C9E1',
      'media_type': 'IMAGE',
      'like_count': 57826,
      'comments_count': 388,
      'timestamp': '2020-06-09T09:55:46+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBNceHcgl6R/',
      'id': '17874951385728643'},
     {'caption': 'महान स्वतंत्रता सेनानी एवं जननायक भगवान बिरसा मुंडा जी की पुण्यतिथि पर विनम्र श्रद्धांजलि।',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/103280597_3057825094254797_3884304578204713535_n.jpg?_nc_cat=103&_nc_sid=8ae9d6&_nc_ohc=jqN4UkGWW_kAX8XLrPR&_nc_ht=scontent.cdninstagram.com&oh=e1e1ed4e64c49abc7623e75857390a13&oe=5F168630',
      'media_type': 'IMAGE',
      'like_count': 35190,
      'comments_count': 170,
      'timestamp': '2020-06-09T06:33:14+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBNFSrDgIIR/',
      'id': '17843311712229115'},
     {'caption': 'Odisha #BJPJanSamvad in pictures...',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102688611_111240973800675_3675080288425326366_n.jpg?_nc_cat=100&_nc_sid=8ae9d6&_nc_ohc=gH6s-vPJf78AX-tKsF5&_nc_ht=scontent.cdninstagram.com&oh=8d4d7af55f801525aaabdd2752c0b813&oe=5F18153E',
      'media_type': 'IMAGE',
      'like_count': 33874,
      'comments_count': 203,
      'timestamp': '2020-06-08T17:25:45+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBLrK_Zgc69/',
      'id': '18056941192242702'},
     {'caption': 'बिहार के जन-जन ने सुनी #बिहार_जनसंवाद रैली...',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/102705657_274392950281791_8017325389862027533_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=gucFSfG15pgAX-wrFMW&_nc_ht=scontent.cdninstagram.com&oh=a9e66393c568ae5386b05ca989e76020&oe=5F17EEB4',
      'media_type': 'IMAGE',
      'like_count': 44691,
      'comments_count': 349,
      'timestamp': '2020-06-07T18:23:54+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBJNCFCABHg/',
      'id': '17850850097105388'},
     {'caption': 'BJP National President Shri jpnaddaofficial plants a sapling on #WorldEnvironmentDay.',
      'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/103183755_832763770583557_8700377016758320263_n.mp4?_nc_cat=107&vs=17948495521346275_1104447547&_nc_vs=HBksFQAYJEdJdDFKZ1lGT3Jyc1pQVUNBSWM4MnRmTThyMTRia1lMQUFBRhUAAsgBABUAGCRHTzd5SWdibE9fNTlKVEFMQVBqaFgzQ1lUbEV3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFsbYi6P4g%2BI%2FFQIoAkMzLBdAOAi0OVgQYhgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=pqswPNjUho8AX8gpj3q&_nc_ht=video.fdel1-2.fna&oh=6301d7e55708b8a2264ab6cac9877cc3&oe=5F1740C6&_nc_rid=f9f39f2727',
      'media_type': 'VIDEO',
      'like_count': 26635,
      'comments_count': 211,
      'timestamp': '2020-06-05T08:22:51+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBC-o0PA69a/',
      'id': '18118938049113698'},
     {'caption': "I wish I could be there for what has become the famous 'Modi hug' & have my share of samosas. Next time, it will have to be the Gujarati Khichdi. I will try that in the kitchen before next time we meet in person: Australian PM scottmorrisonmp\n.\n.\nPM narendramodi and Australian PM scottmorrisonmp address 1st virtual India-Australia summit. #india #modihug #bjp #australia",
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/101815786_689123381939267_7050305340797946967_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=KqRBMzlminEAX9ZME2p&_nc_ht=scontent.cdninstagram.com&oh=782d2ca5255b711b8bb4f04560811484&oe=5F1506E5',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 106232,
      'comments_count': 518,
      'timestamp': '2020-06-04T07:58:59+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBAXIaAFEwv/',
      'id': '17867225362830120'}]




```python
 x[0]['business_discovery']['media']['data'][0:10]
```




    [{'caption': 'लड़ाई जारी है लेकिन हौसले बुलंद है। जीतेंगे हम...',
      'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/105281340_196641258291866_7205467741881983526_n.mp4?_nc_cat=100&vs=17869559734829517_3228560770&_nc_vs=HBksFQAYJEdEeDNSZ2FhUWxrYzJMSUFBQ1ppYVN1ODl2NWpia1lMQUFBRhUAAsgBABUAGCRHTWphT1FiZzRlMjRVdzREQU1CUFp5T05uVVVJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFpq8%2BtOikb4%2FFQIoAkMzLBdAPirAgxJumBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=AW8hg-F_MkIAX_4qXXe&_nc_ht=video.fdel1-4.fna&oh=177c7874d52c3b0a600436b702aa01b1&oe=5F1767E5&_nc_rid=0b3942b744',
      'media_type': 'VIDEO',
      'like_count': 16018,
      'comments_count': 66,
      'timestamp': '2020-06-22T05:48:45+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBuegpTAQRn/',
      'id': '17863465609926295'},
     {'caption': 'BJP National President Shri jpnaddaofficial performs yoga at his residence on #InternationalYogaDay today. #MyLifeMyYoga',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104053466_2317964778511660_5981624510555492019_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=JUPXH3DmOxMAX8y1O3N&_nc_ht=scontent.cdninstagram.com&oh=0a19fa241fd1c3d68c7856f2ca2b2a75&oe=5F15DE50',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 63768,
      'comments_count': 148,
      'timestamp': '2020-06-21T04:02:50+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBrtnoggN_k/',
      'id': '18059996809227284'},
     {'caption': 'कोरोना के संकटकाल में भी टेक्नोलॉजी के माध्यम से देश के जन-जन तक पहुंच रही है भारतीय जनता पार्टी। आज भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial के राजस्थान जनसंवाद रैली में संबोधन को सुनते आमजन।',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105414284_265420581539185_4630206849005528189_n.jpg?_nc_cat=111&_nc_sid=8ae9d6&_nc_ohc=Hxn-B9z-d0EAX_IB2AH&_nc_ht=scontent.cdninstagram.com&oh=e719ea92eab6f1b1961397dfb105502e&oe=5F157E9D',
      'media_type': 'IMAGE',
      'like_count': 34851,
      'comments_count': 118,
      'timestamp': '2020-06-20T13:37:31+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBqKlz4ASym/',
      'id': '18091724080175849'},
     {'caption': 'राहुल गांधी, सुनिए हमारे वीर जवान के वीर पिता की भावनाओं को और बंद कीजिए उनके नाम पर निकृष्ट राजनीति। #india #bjp #china',
      'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104735923_1188447364835330_3114894258955085295_n.mp4?_nc_cat=100&vs=17877093337693291_566229461&_nc_vs=HBksFQAYJEdMTWtQZ1lDNkFQMzRqZ0VBTy1sNnpuVFV6b3Jia1lMQUFBRhUAAsgBABUAGCRHR0NaT1FhUWRuQ1BreVlCQU1XdXdwd1V0UmtJYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFtaZosnkx8E%2FFQIoAkMzLBdAQEiTdLxqfxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjQ4MC5mZWVkIn0%3D&_nc_ohc=0REsp84tcW8AX9F6h3j&_nc_ht=video.fdel1-4.fna&oh=1159a1ac7de66f95cd74591ff9055f93&oe=5F1764F9&_nc_rid=7c1a08f482',
      'media_type': 'VIDEO',
      'like_count': 19614,
      'comments_count': 179,
      'timestamp': '2020-06-20T05:01:07+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBpPeZxAd5z/',
      'id': '17887502845575049'},
     {'caption': 'भाजपा राष्ट्रीय अध्यक्ष श्री jpnaddaofficial 20 जून 2020 को दोपहर 12.30 बजे वीडियो कॉन्फ़्रेंसिंग के माध्यम से राजस्थान जनसंवाद रैली को संबोधित करेंगे। BJP4Rajasthan',
      'media_url': 'https://video.fdel1-2.fna.fbcdn.net/v/t50.2886-16/104265490_292049665296242_423465061768528093_n.mp4?_nc_cat=107&vs=17857036247024519_3284310992&_nc_vs=HBksFQAYJEdCTDNOZ1p5aDQ0Y25na0JBTjJBZ09VNmNfQUZia1lMQUFBRhUAAsgBABUAGCRHSDZYT0FZS0hFWklvLUVBQUc5Y3c3ZmJrMlpvYmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFo7X66enuLg%2FFQIoAkMzLBdANV3ztkWhyxgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=saabCtPvwukAX83CWTS&_nc_ht=video.fdel1-2.fna&oh=4f35aada4816b6b365a2b0446cc5a66f&oe=5F15A1C1&_nc_rid=4ea34c4e61',
      'media_type': 'VIDEO',
      'like_count': 16005,
      'comments_count': 44,
      'timestamp': '2020-06-19T17:11:30+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBn-QQ9FWKa/',
      'id': '18152066587031624'},
     {'caption': 'PM narendramodi holds All Party Meeting to discuss situation in India-China border areas\n.\n.\n20 of our brave soldiers made the supreme sacrifice in Ladakh but also taught a lesson to those who dared to look towards our motherland. Neither is anyone inside our territory nor is any of our post captured; India wants peace and friendship, but upholding sovereignty is foremost: PM narendramodi',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/104101998_579856346007751_1019788892395299541_n.jpg?_nc_cat=1&_nc_sid=8ae9d6&_nc_ohc=tacps046vWcAX8u0QB2&_nc_ht=scontent.cdninstagram.com&oh=ec16af88a1bad743b7948aea877bc480&oe=5F17339C',
      'media_type': 'CAROUSEL_ALBUM',
      'like_count': 88308,
      'comments_count': 319,
      'timestamp': '2020-06-19T16:36:37+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBn6Sz0gg-V/',
      'id': '17888904943571172'},
     {'caption': "Modi govt's huge relief to Delhiites. \nOn instructions of Home Minister Shri amitshahofficial, the cost of treatment of COVID-19 patients in private hospitals of Delhi has been reduced by about two-thirds.\n\nPPE kits and medicines are also included in the new rates.",
      'media_url': 'https://scontent.cdninstagram.com/v/t51.2885-15/105020102_191367085579754_6719776562378654198_n.jpg?_nc_cat=110&_nc_sid=8ae9d6&_nc_ohc=cUJkZK9oWeUAX8bCrdX&_nc_ht=scontent.cdninstagram.com&oh=9c5485f63f3e7558279e69169bcc28b2&oe=5F16869C',
      'media_type': 'IMAGE',
      'like_count': 28970,
      'comments_count': 269,
      'timestamp': '2020-06-19T13:26:29+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBnkiO9gXcK/',
      'id': '17875144507732012'},
     {'caption': 'BJP has decided to postpone all its political programmes including virtual rallies for next 2 days.',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/104103516_103667658011266_3962349400865496458_n.jpg?_nc_cat=104&_nc_sid=8ae9d6&_nc_ohc=SrzDIB3ShaYAX9rdr23&_nc_ht=scontent.cdninstagram.com&oh=3370eb484c2794f990b23eb2f3b8b697&oe=5F1733FD',
      'media_type': 'IMAGE',
      'like_count': 23698,
      'comments_count': 145,
      'timestamp': '2020-06-18T06:09:47+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBkNw3AAJ0A/',
      'id': '18121635580113888'},
     {'caption': '1857 के प्रथम स्वतंत्रता संग्राम में अंग्रेज़ी शासन के विरुद्ध अग्रिम भूमिका निभाकर अपने प्राणों की आहुति देने वाली महान वीरांगना रानी लक्ष्मीबाई की पुण्यतिथि पर कोटि-कोटि नमन।',
      'media_url': 'https://scontent.cdninstagram.com/v/t51.29350-15/103661980_566983254001582_7367512126551480632_n.jpg?_nc_cat=108&_nc_sid=8ae9d6&_nc_ohc=C5KmytflgHYAX-jQdzx&_nc_ht=scontent.cdninstagram.com&oh=cb83d40338ed9cd684123c8b47109659&oe=5F16ECD6',
      'media_type': 'IMAGE',
      'like_count': 37857,
      'comments_count': 231,
      'timestamp': '2020-06-18T04:33:14+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBkCtskA-wB/',
      'id': '17874635890734764'},
     {'caption': 'भारत शांति चाहता है, लेकिन भारत उकसाने पर हर हाल में यथोचित जवाब देने में सक्षम है। हमारे दिवंगत शहीद वीर जवानों के विषय में देश को इस बात में गर्व होगा कि वे मारते-मारते मरे हैं: प्रधानमंत्री श्री narendramodi',
      'media_url': 'https://video.fdel1-4.fna.fbcdn.net/v/t50.2886-16/104485235_2728637797458196_1083507323252640862_n.mp4?_nc_cat=102&vs=17876598496707417_2072603921&_nc_vs=HBksFQAYJEdITlJPZ1lVWWFOX3JyRUpBRjRNQW5vclpBa1Bia1lMQUFBRhUAAsgBABUAGCRHS2YwTmdZQ0lIVjRYQUVKQUFrWHVCYl85Ynd3YmtZTEFBQUYVAgLIAQAoABgAGwGIB3VzZV9vaWwBMRUAABgAFrLqvqv9qsE%2FFQIoAkMzLBdARfeNT987ZBgSZGFzaF9iYXNlbGluZV8xX3YxEQB16gcA&_nc_sid=59939d&efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5mZWVkIn0%3D&_nc_ohc=JTZii5Y9M0oAX-V7vRo&_nc_ht=video.fdel1-4.fna&oh=8183b16ee1a4786bb958993128c4bfdc&oe=5F15687B&_nc_rid=b66e01f968',
      'media_type': 'VIDEO',
      'like_count': 32520,
      'comments_count': 454,
      'timestamp': '2020-06-17T15:54:43+0000',
      'owner': {'id': '17841400193077467'},
      'permalink': 'https://www.instagram.com/p/CBir3VWARag/',
      'id': '18110380408137861'}]




```python
x[0]['business_discovery']['media']['data'][0:10][0]['caption']
```




    'लड़ाई जारी है लेकिन हौसले बुलंद है। जीतेंगे हम...'




```python
import json
with open('C:/Users/mayan/Desktop/1TouchSolutions/Twitterdata_features/2016-11-18_15-05-51_UTC_comments.json', encoding='utf-8') as f:
    x = json.loads(f.read())
    print(x)
```

    [{'id': 17844687676191763, 'created_at': 1479725635, 'text': 'Nice!', 'owner': {'id': '3925656471', 'is_verified': False, 'profile_pic_url': 'https://instagram.fdel1-4.fna.fbcdn.net/v/t51.2885-19/s150x150/14334579_312085085834687_6757088205016662016_a.jpg?_nc_ht=instagram.fdel1-4.fna.fbcdn.net&_nc_ohc=Da5xDRRAgLoAX-apyqY&oh=119b611d98b36f8dfdaa2ba437c13213&oe=5F24524F', 'username': 'wouldyourather_app'}, 'likes_count': 0, 'answers': []}]
    


```python
x[0]
```




    {'id': 17844687676191763,
     'created_at': 1479725635,
     'text': 'Nice!',
     'owner': {'id': '3925656471',
      'is_verified': False,
      'profile_pic_url': 'https://instagram.fdel1-4.fna.fbcdn.net/v/t51.2885-19/s150x150/14334579_312085085834687_6757088205016662016_a.jpg?_nc_ht=instagram.fdel1-4.fna.fbcdn.net&_nc_ohc=Da5xDRRAgLoAX-apyqY&oh=119b611d98b36f8dfdaa2ba437c13213&oe=5F24524F',
      'username': 'wouldyourather_app'},
     'likes_count': 0,
     'answers': []}




```python
x[0]['id']
```




    17844687676191763




```python
x[0]['text']
```




    'Nice!'




```python
x[0]['owner']['id']
```




    '3925656471'




```python
x[0]['owner']['username']
```




    'wouldyourather_app'




```python
x[0]['likes_count']
```




    0




```python
x[0]['answers']
```




    []




```python

```
