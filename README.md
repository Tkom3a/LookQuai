# LookQuai  
  
Бот для мониторинга цены QUAI на бирже MEXC. Отслеживает изменения цены и отправляет уведомления в Telegram канал при превышении заданных порогов роста или падения.  
  
Также присылает приветственное сообщение и уведомления в Telegram в формате:  
  
🤖 LookQuai - Bot Started  
  
✅ Monitoring active  
📊 Pair: QUAIUSDT  
📈 UP threshold: 4.0%  
📉 DOWN threshold: 4.0%  
⏱ Lookback: 5 minutes  
🔄 Check interval: 60 seconds  
📢 Channel: @my_quai_channel  
  
💰 Current price: 0.00012345 USDT  
🕐 Time: 14:00:00  
  
📡 Monitoring started successfully  
  
🚀 📈 PRICE INCREASE  
  
Price changed by +5.23% over last 5.0 minutes  
  
Old price: 0.00011730 USDT  
New price: 0.00012345 USDT  
Absolute change: +0.00000615 USDT  
  
🕐 Time: 14:05:00  
  
📉 📉 PRICE DECREASE  
  
Price changed by -4.50% over last 5.0 minutes  
  
Old price: 0.00012345 USDT  
New price: 0.00011790 USDT  
Absolute change: -0.00000555 USDT  
  
🕐 Time: 14:10:00  
  
## Установка  
  
git clone https://github.com/Tkom3a/LookQuai.git  
cd LookQuai  
  
  
## Билд и запуск  
  
docker compose up -d --build  
  
  
## Логи  
  
docker compose logs -f  
  
## Остановка и удаление  
  
docker compose down  
docker rmi lookquai-bot  
chmod +x uninstall.sh  
./uninstall.sh  
