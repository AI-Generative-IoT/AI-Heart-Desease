❤️🧠 AI-Heart-Disease  

Modellentwicklung für die Analyse von Herzerkrankungen

👥 Autoren  

Betül Yurtman   
Dr. Alexej Schelle  


🧾 1. Zusammenfassung (Abstract)  

Das Projekt AI-Heart-Desease untersucht systematisch die Eignung unterschiedlicher prädiktiver Modellierungsansätze zur Klassifikation und Analyse von Ursachen von Herzerkrankungen. Der Fokus liegt auf dem Vergleich zwischen zufallsbasierten (randomisierten) Modellen und neuronalen Netzwerken als generative Modelle.   

Basierend auf früheren Erkenntnissen aus der Analyse psychologischer Erkrankungen wird überprüft, ob auch bei Herzerkrankungen eine komplementäre Leistungsfähigkeit dieser Modellklassen existiert. Ziel ist es, allgemeine Kriterien für eine fundierte Modellselektion in der medizinischen Risiko- und Wahrscheinlichkeitsvorhersage abzuleiten.  


🎯 2. Projektziele  

📊 Statistische Analyse von Ursachen und Risikofaktoren von Herzerkrankungen  
🧠 Entwicklung neuronaler Netzwerke zur generativen Mustererkennung  
🎲 Einsatz von Zufalls- und Baseline-Modellen als Referenz  
📈 Untersuchung der Skalierung der Vorhersagegenauigkeit  
🔄 Vergleich mit Ergebnissen aus psychologischen Krankheitsmodellen  
🧭 Ableitung allgemeiner Modellselektionsstrategien  


🗂️ 3. Datenbasis und Merkmalsgruppen  

📁 Datentypen  
👤 Demografie (Alter, Geschlecht)  
❤️ Physiologie (Blutdruck, Cholesterin, Herzfrequenz)  
🚬 Lebensstil (Rauchen, Aktivität, Ernährung)  
🏥 Klinische Parameter und Diagnosen  
⚙️ Vorverarbeitung  

Normalisierung numerischer Werte  
Umgang mit fehlenden Daten  
Kodierung kategorialer Merkmale  


🧩 4. Modellarchitekturen  

🎲 4.1 Zufalls- und Baseline-Modelle  

Zufallsmodelle dienen als statistische Nullhypothese:  
Zufällige Klassifikation unter Berücksichtigung der Klassenverteilung  
Einfache probabilistische Modelle mit minimalen Annahmen  

➡️ Ziel: Bewertung, ob Krankheitsmuster signifikant über Zufall hinausgehen.  

🧠 4.2 Neuronale Netzwerke (Generative Modelle)  

Neuronale Netze modellieren komplexe Abhängigkeiten:  

Nichtlineare Feature-Interaktionen  
Latente Repräsentationen von Risikofaktoren  
Adaptive Gewichtsanpassung durch Training  

➡️ Einsatz von Regularisierung und Validierung zur Vermeidung von Overfitting.  


📏 5. Evaluationsmethoden  

📊 Metriken  
✔️ Genauigkeit (Accuracy)  
🎯 Präzision & Recall  
🧮 F1-Score  
🔀 Konfusionsmatrix  
🔁 Validierung  

Kreuzvalidierung  

Analyse der Stabilität über Subgruppen  


🔍 6. Vorläufige Ergebnisse  

❌ Zufalls- und neuronale Modelle erzielen selten gleichzeitig hohe Genauigkeiten  
🧠 Strukturierte Krankheitsbilder profitieren stark von neuronalen Netzen  
🎲 Andere Klassen zeigen nur geringe Abweichung von Zufallsmodellen  
➡️ Hinweis auf unterschiedliche Grade struktureller Vorhersagbarkeit


💬 7. Diskussion  

Die Ergebnisse legen nahe, Herzerkrankungen nach ihrer Modellierbarkeit zu unterscheiden:  

🎲 Zufallsdominierte Erkrankungen – hohe Heterogenität, geringe Struktur  
🧠 Generativ-dominierte Erkrankungen – komplexe, aber lernbare Muster  
➡️ Konsequenz: adaptive und krankheitsspezifische Modellwahl  


🚀 8. Fazit und Ausblick  

Das Projekt bestätigt, dass Modellselektion ein kritischer Faktor in medizinischer KI ist. Eine pauschale Anwendung neuronaler Netze ist nicht immer optimal.  

🔮 Zukünftige Arbeiten  

Erweiterung der Datensätze  
Hybride und Ensemble-Modelle  
Verbesserte Interpretierbarkeit (Explainable AI)  

🏷️ Schlüsselwörter  

Herzerkrankungen · Maschinelles Lernen · Neuronale Netze · Zufallsmodelle · Medizinische KI  


🔗 9. Ressourcen & Links  

📂 Code & Projekt  

GitHub: https://github.com/your-org/AI-Heart-Desease  

📊 Datensätze  

UCI Heart Disease Dataset: https://archive.ics.uci.edu/ml/datasets/Heart+Disease  

Kaggle Heart Disease Dataset: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset  

📚 Medizinische Quellen  

WHO – Herz-Kreislauf-Erkrankungen: https://www.who.int/health-topics/cardiovascular-diseases  
American Heart Association: https://www.heart.org/  

🧠 ML-Frameworks  

TensorFlow: https://www.tensorflow.org/  
PyTorch: https://pytorch.org/  
Scikit-learn: https://scikit-learn.org/  


🎨 10. Icons & Favicon-Konzept  

❤️🧠 Projekt-Icon  

Herzform mit integrierten neuronalen Knoten  
Farbkonzept: Rot (Medizin) + Blau (KI)  

📐 Empfohlene Favicon-Dateien  

favicon.ico (16×16, 32×32)  
favicon-32x32.png  
favicon-192x192.png  
apple-touch-icon.png (180×180)  

🛠️ Favicon-Generatoren  

https://favicon.io/  
https://realfavicongenerator.net/


🏷️ About Contributors
Interested contributors may submit ideas to ejp@krealix.de. Discussion and short lectures can be arranged at https://calendly.com/alexej-schelle/.
