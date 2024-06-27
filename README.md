![download](https://github.com/umutokcurmr/starup-portfoyum/assets/132665364/958ac6ed-cf2c-405b-837a-6aa751eaaf7d)
# startup-portfoyum
# yeni kurulan girişimlere fon sağlıyorum
import matplotlib.pyplot as plt
# Veri
labels = ['Mapla\nFonlaBüyüsün', 'Atronmac\nFonbulucu', 'Mua\nValü', 'Jidoka\nFonangels']
sizes = [25, 25, 25, 25]  # Her dilim eşit olacak şekilde yüzde dağılımı
colors = ['blue','yellow','red','orange']  # Dilim renkleri
# Pasta grafiği oluşturma
fig1, ax1 = plt.subplots()
ax1.pie(sizes, labels=labels, colors=colors, autopct='%1.1f%%',
        startangle=90)
# Grafiğin eşit daire şeklinde görünmesi için
ax1.axis('equal')
# Başlık ekleme
plt.title('STARUP PORTFÖYÜM')
# Görseli kaydetme
# Grafik gösterimi
plt.show()
