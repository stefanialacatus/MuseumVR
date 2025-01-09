# MuseumVR
Echipa : Iacobut Denisa-Delia, Lacatus Stefania, Luca Stefan, Bujenita Lucian Andrei  
Tema 4 - State of Art : https://docs.google.com/document/d/1OIpAWMyxomGPD35lBTiM_nPHP0qbptriDZW8LR0nyrs/edit?usp=sharing  
Tema 5 - Main Modules : https://docs.google.com/document/d/1RX53seIkyrbv4tn8caDvxJ88YlNsD5gCPYujDZNAz6Y/edit?tab=t.0#heading=h.bcldxwdefncd  

# Progres Saptamana 7 : https://youtu.be/FR9kOHwHV6s  
  Resurse folosite :   
  https://www.myminifactory.com/object/3d-print-statue-of-athena-parthenos-35915    
  https://www.myminifactory.com/object/3d-print-statue-of-juno-41092    
  https://www.myminifactory.com/object/3d-print-statue-of-hygeia-71783    
  https://www.myminifactory.com/object/3d-print-venus-aphrodite-is-the-goddess-of-love-she-was-depicted-in-the-nude-or-in-various-stages-of-nudity-and-painted-the-figure-is-executed-in-the-hellenistic-style-and-famed-for-its-sensuous-appearance-it-supposedly-lost-its-arms-in-a-struggle-arising-b-25162     
  https://www.myminifactory.com/object/3d-print-eros-with-a-dolphin-94133    

  # Progres Saptamana 10 : https://youtu.be/Jg3SoUu3ROU  
  - Am transferat proiectul din Blender in Unity :
      - Am adaugat posibilitatea de a testa jocul si de pe laptop (se activeaza PlayerController), pe langa cu VR headset (VR Rig), verificarea se face printr-un script atasat de obiectul GameManager  
      - Sistemul de locomotie => jucatorul se poate misca si plimba prin incaperi cu ajutorul unui script PlayerMovements  
      - Am adaugat colliders pentru pereti si statui/alte obiecte  
  - Model puzzle-uri si intrebari/ghicitori :https://www.figma.com/design/ITDKPUTQ5JUUdbSCS0Ie7V/Untitled?node-id=0-1&t=o2e44xKUNVaCDy2c-1
  # Progres Săptămâna 11 : https://docs.google.com/document/d/1nAovqwcW1MdFinDa14OjRv4CdHAibXmLBoZpaIHvqnc/edit?tab=t.0
  - Am adăugat funcționalitățile necesare pentru vizualizarea unui singur exponat la început, iar afișarea celorlalte pe rând după rezolvarea unui puzzle sau ghicitoare.
  - Am adăugat picturile în muzeu
  - Am modelat partea de puzzle și ghicitori printr-un pergament ce conține informațiile necesare
  - Am adăugat funcționalitățile pentru asistentul virtual împreună cu afișarea informațiilor în dreptul fiecărui exponat.  

# Progres Saptamana 12 : https://youtu.be/EFypD-mKnkk  
- Am modelat quizz-urile pentru fiecare exponat in Blender si le-am importat in Unity  
- Am asezat quizz-ul specific unui exponat in fata sa si l-am conectat de un collider si un script pentru a aparea cand te apropii de locul acelui exponat, doar daca acesta este ascuns (inactiv), adica trebuie "descoperit" prin rezolvarea quizz-ului
- Am adaugat vocea Asistentului Virtual : introducere in joc la intrare si informatii despre fiecare exponat, pornite cu ajutorul unui script cand se intra in contact cu collider-ul specific
- Functia de "ascundere" a tuturor exponatelor mai putin unul in fiecare camera (statui si picturi)  

# Progres Saptamana 13   
Glow pentru Exponate Deblocate
-Am implementat un efect vizual de strălucire pentru exponatele deblocate, utilizând materiale cu Emission și post-procesare pentru un impact estetic sporit.

Eliminarea Hinturilor de pe Pergamente
-Hinturile au fost eliminate pentru a crește gradul de explorare și a încuraja o experiență mai interactivă.

Scripturi pentru Textbox și Buton
-Am adăugat scripturi care gestionează validarea textelor de raspuns cand butonul este apasat.
