<pre>
PS C:\Users\Elliot-Chan> Get-Profile
Name                         Value
----                         -----
Name                         Elliot Chan
OS                           Windows 11
Uptime                       22 Years

  
PS C:\Users\Elliot-Chan> Get-CodingInterests

Name                           Value
----                           -----
Bioinformatics                 Active
Data Analysis                  Active
Visualizations                 Active
Machine Learning               Active
Life Sciences Applications     Active

PS C:\Users\Elliot-Chan> Write-Host "Currently working on more features for: NOCTURNAL" -ForegroundColor Cyan
Currently working on more features for: NOCTURNAL

  
PS C:\Users\Elliot-Chan> Get-Project -Name NOCTURNAL | Format-List

Name        : NOCTURNAL v2.0.0
Description : Exploring the dark chemical space
URL         : <a href="https://github.com/Elliot-Chan-120/NOCTURNAL-v2.0.0/blob/main/README.md" target="_blank">https://github.com/Elliot-Chan-120/NOCTURNAL-v2.0.0/blob/main/README.md</a>
Tags        : @{DrugDiscovery="8A2BE2"; MachineLearning="FF6F00"; ChemicalAnalysis="2C8EBB"}
Summary     : A database navigation-aided interface for training ML models on drug-protein potency
              & compound molecular fingerprint analysis. The system can apply these models to
              predict any chemical compounds' potencies against target proteins, and further
              optimize drug structures using my molecular optimization algorithm system "MutaGen".

  
PS C:\Users\Elliot-Chan> Get-ContactInfo | Format-Table

Protocol        Address                          Link
--------        -------                          ----
LinkedIn        elliot-chan-6206b01ba            <a href="https://linkedin.com/in/elliot-chan-6206b01ba/" target="_blank">LinkedIn Profile</a>
Email           elliotchan120@gmail.com          <a href="mailto:elliotchan120@gmail.com">elliotchan120@gmail.com</a>

  
PS C:\Users\Elliot-Chan> Get-TechStack

Python    NumPy    Pandas    scikit-learn    Matplotlib    Plotly    PowerShell

  
PS C:\Users\Elliot-Chan> Get-GitHubStats | Out-Host

GitHub stats loading...
View comprehensive stats at: <a href="https://github.com/Elliot-Chan-120" target="_blank">https://github.com/Elliot-Chan-120</a>

PS C:\Users\Elliot-Chan> _
</pre>

