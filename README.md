import logging
from datetime import datetime

logging.basicConfig(level=logging.INFO, filename="task1.log", filemode="w",
                    format="%(asctime)s - %(levelname)s - %(message)s")

date_str = datetime.now().strftime("%Y-%m-%d")
logging.info(f"Поточна дата: {date_str}")

print("Готово! Повідомлення записано в task1.log")
