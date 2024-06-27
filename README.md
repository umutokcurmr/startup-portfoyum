![download](https://github.com/umutokcurmr/startup-portfoyum/assets/132665364/d5fe22ea-3eac-4490-82cf-4e8a77b0e4b0)

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
plt.title('STARTUP PORTFÖYÜM')
# Görseli kaydetme
# Grafik gösterimi
plt.show()
