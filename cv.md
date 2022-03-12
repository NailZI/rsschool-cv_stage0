# Nail Ishkinin
---
## Contacts
* Phone: +7 919 634-07-60
* E-mail: dubletrain76@gmail.com

## About Me

## Skills
* HTML
* CSS
* Python
* Git, github
* VS Code, IntelliJ IDEA, PyCharm

## Courses:

[Python-разработка для начинающих](https://netology.ru/backend/api/user/programs/25521/pdf_certificate/)
[The basics of Python programming](https://letpy.com/certificate/7033ccfa-6b62-4e34-b4dc-2b8783dcc48c/en/)


## Code Example

'''
    import time
    from pythonping import ping
    from logs import logger


    def response(hostname):
        try:
            m = ping(hostname, timeout=3, count=3)
            time.sleep(1)
        except Exception as err:
            m = f'ping IP {hostname} не доступен!\n' + str(err)
            #logger('no_user', m)
        return m


    if __name__ == '__main__':
        host_1 = '159.159.2.166'
        host_2 = '1.1.1.2'
        print(host_1, '\n', response(host_1))
        print(host_2, '\n', response(host_2))
'''

## Language
* English A0
* Russian -Native

