# Få din Arlo (eller anden overvågning) til at samarbejde med Google AI 

Det giver dig mulighed for at AI giver dig nogle respons ud fra de billeder den ser på dit kamera. 

Først og fremmest skal du igennem HACS downloade integrationen - I det her tilfælde Arlo. 

Derudover skal du bruge følgende integrationer: 

Google AI: https://www.home-assistant.io/integrations/google_generative_ai_conversation/

!! Husk selvfølgelig at genstarte din HA efter installation !! 

Åben derefter konfigurationerne og skab en kode: 

Opret derefter en automation: "Camera 1 - Snapshot on motion" - kopier koden jeg har lagt ind. 

Når du har lagt koden ind i automationen, så kan du gå tilbage til "rediger i visuel editor" og vælge den entity som er dit kamera/motionsensor. 

Når du er færdig, så opretter du et script og indesætter koden som jeg har lavet under "script"

Når du er færdig, så burde dit kamera kører med Google AI ;) 

Skriv på Facebook hvis de driller, så skal jeg nok se om jeg ikke kan hjælpe! 


/Sammen har vi det sjovere! 
