# Nice_rep
A really nice rep
№ I will be posting my solved exercises every day.

num1 = int(input())
num2 = num1+1
num3 = num2+1
print(num1)
print(num2)
print(num3)



num1, num2 = int(input()), int(input())
print(num1, "+", num2, '=', (num1 + num2))
print(num1, "-", num2, '=', (num1 - num2))
print(num1, "*", num2, '=', (num1 * num2))



chislo = int(input())
num1 = chislo // 1000
num2 = chislo % 1000 // 100
num3 = chislo % 100 // 10
num4 = chislo % 10
print('Цифра в позиции тысяч равна', num1)
print('Цифра в позиции сотен равна', num2)
print('Цифра в позиции десятков равна', num3)
print('Цифра в позиции единиц равна', num4)


a = int(input())
b = int(input())
c = int(input())
d = int(input())
da = 0
net = 0
a != b != c != d
if a < b:
    da = a
else:
    da = b
if c < d:
    net = c
else: 
    net = d
if da < net:
    print(da)
else:
    print(net)
    
    
    import telebot

bot = telebot.TeleBot('2109044481:AAF4Hs7_3JgdI3zThVodj-rOv5a2btWm6pQ')




@bot.message_handler(content_types={'text'})
def get_text_messages(message):
    if message.text == "Привет":
        bot.send_message(message.from_user.id, "Привет, чем я могу тебе помочь?")

    elif message.text == "Кто я":
        bot.send_message(message.from_user.id, message.from_user)
    elif message.text == "/help":
        bot.send_message(message.from_user.id, "Напиши привет")
    else:
        bot.send_message(message.from_user.id, "Я тебя не понимаю. Напиши /help.")


bot.polling(none_stop=True, interval=0)

a = int(input())
b = int(input())
c = int(input())
a1 = 0
b1 = 0
c1 = 0
if a > 0:
    a1 = a
if b > 0:
    b1 = b
if c > 0:
    c1 = c
print(a1 + b1 + c1)    
