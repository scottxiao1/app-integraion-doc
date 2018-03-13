广告请求和返回json示例
=============================

广告请求json示例
-----------------------------------------


.. code-block:: json
    :linenos:

    {
        "id":"m83390492620425",
        "app":{
            "id":"2",
            "publisher":{
                "id":"1"
            }
        },
        "device":{
            "devicetype":1,
            "make":"apple",
            "model":"iphone",
            "hwv":"2",
            "os":"1",
            "osv":"11.0.1",
            "size":"640x960",
            "pixel_ratio":1,
            "screen_density":1.0,
            "screen_orientation":1,
            "ua":"Mozilla/5.0 (iPhone; U; CPU iPhone OS 4_3_2 like Mac OS X; en-us) AppleWebKit/533.17.9 (KHTML, like Gecko) Version/5.0.2 Mobile/8H7 Safari/6533.18.5",
            "ip":"1.1.1.1",
            "ifa":"ifa",
            "ifa_md5":"ifa_md5",
            "android_id":"android_id",
            "android_id_md5":"android_id_md5",
            "imei":"imei",
            "imei_md5":"imei_md5",
            "mac":"mac",
            "mac_md5":"mac_md5",
            "duid":"duid",
            "duid_md5":"duid_md5"
        },
        "network":{
            "type":1,
            "operator":1,
            "cellular_id":"1",
            "wifis":[
                {
                    "mac":"1",
                    "rssi":"1"
                }
            ]
        },
        "adpos":[
            {
                "pos_id":"2",
                "capacity":1
            }
        ]
    }

广告返回json示例
-----------------------------------------

.. code-block:: json
    :linenos:


    {
    "success":true,
    "id":"0922",
    "nbr":0,
    "bidid":"932916559284809546",
    "ads":[
        {
            "id":"932916559406522191",
            "price":0.1,
            "cost_type":2,
            "pos_id":"10000",
            "interaction_type":1,
            "creative_elements":{
                "image":"https://saascdn.xxxx.cn/c-34a29424-f13b-402c-aa5d-02a910940adb.jpg"
            },
            "site_url":"http://www.adxing.com",
            "click_tracking_url":"https://mmptr.limei.com/mtx/c?id=932916559406522191",
            "imp_tracking_urls":[
                "http://www.adxing.com",
                "https://mbptr.adxing.cn/at/i?id=932916559406s522191",
                "https://mmptr.adxing.com/mtx/i?id=932916559406522191"
            ]
        }
     ]
    }
