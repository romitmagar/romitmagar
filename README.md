- 👋 Hi, I’m @romitmagar
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
romitmagar/romitmagar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
java.lang.RuntimeException: 

MSA Error: 401: Unauthorized, error stream:
{"Identity":"0","XErr":2148916233,"Message":"","Redirect":"https://start.ui.xboxlive.com/CreateAccount"}
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.throwResponseError(Msa.java:293)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireXsts(Msa.java:169)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireXBLToken(Msa.java:122)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireAccessToken(Msa.java:75)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.<init>(Msa.java:35)
	at net.kdt.pojavlaunch.
.microsoft.MicrosoftAuthTask.doInBackground(MicrosoftAuthTask.java:72)
	at net.kdt.pojavlaunch.authenticator.microsoft.MicrosoftAuthTask.doInBackground(MicrosoftAuthTask.java:22)
	at android.os.AsyncTask$2.call(AsyncTask.java:305)
	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:243)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
	at java.lang.Thread.run(Thread.java:761)
