# Wake-on-LAN (WoL)  
приложение для Wake-on-LAN по локальной сети
![Описание картинки](https://i.pinimg.com/736x/73/5e/e1/735ee1c30cd4aa4392287b6ba3d4759c.jpg)

Технология **Wake-on-LAN** позволяет включать компьютер удаленно через сеть, отправляя специальный "Magic Packet".  

### **Требования:**  
✔ Поддержка WoL в BIOS/UEFI  
✔ Включенная настройка в сетевой карте  
✔ Питание сетевой карты в выключенном состоянии  

### **Как использовать?**  
```bash
wakeonlan XX:XX:XX:XX:XX:XX  # Пример команды в Linux


#### **2. С мини-инструкцией**  
```markdown
## ⚡ Настройка Wake-on-LAN  

1. **Включите WoL в BIOS/UEFI** (обычно в разделе Power Management).  
2. **Настройте сетевую карту** (в Windows: `Диспетчер устройств → Сетевой адаптер → Свойства → Дополнительно → Wake-on-LAN → Включено`).  
3. **Отправьте Magic Packet** через:  
   - Приложения (WoL Utility, TeamViewer)  
   - Команду (Linux: `wakeonlan`, Windows: `PowerShell-скрипт`)  

![WoL в BIOS](https://example.com/wol-bios-settings.jpg)  
