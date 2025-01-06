![image](https://github.com/user-attachments/assets/17579148-8c7c-41c4-9a5f-d697b398bd90)

Bu projede kendi terminalimizi oluşturmaya çalıştık bash'teki gibi içerisinde enviroment barından ve komutlar olan basit bir terminal oluşturma projesi

EXEC: Bir komutun çalıştırılması için kullanılan işlem. execve sistem çağrısıyla bir komut, argümanlar ve çevre değişkenleriyle çalıştırılır.
Örnek: execve("/bin/ls", args, envp)

HEREDOC: << operatörüyle giriş verilerinin bir komuta yönlendirilmesi. Belirtilen ayraç (delimiter) görülene kadar giriş kabul eder.

NV (Environment): Çevre değişkenlerini ifade eder. Shell, çalıştırılacak programlara PATH, HOME gibi bilgileri sağlar.
Örnek: echo $PATH

PIPE: | operatörüyle iki komut arasında veri akışı sağlar. Bir komutun çıktısı diğer komutun girdisi olur.
Örnek: ls | grep txt

REDIRECTION: Komut girdisinin veya çıktısının yönlendirilmesi (>, <).
Örnek: ls > output.txt

TOKENIZATION: Kullanıcı girişinin kelimelere ve sembollere ayrılması.
Örnek: echo "Hello" → ["echo", "Hello"]

PARSING: Girdi komutlarının mantıksal yapılarını çözümleme (ör. argümanlar, operatörler).

FORK: Yeni bir işlem oluşturmak için kullanılan sistem çağrısı.
