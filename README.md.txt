# python_darslarim
ushbu repazetorida python darsiklari joylashtirilgan
n = int(input('Введите количество минут: '))
n = n % (24 * 60)  # ограничиваем количество минут до 24 часов
print('Количество часов:', n // 60, 'Количество минут:', n % 60)
