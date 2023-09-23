# proggetto-n.1
meme_dict = {"CRINGE":"Qualcosa di eccezionalmente strano o imbarazzante","LOL":"Una risposta comune a qualcosa di divertente","ROFL":"ROFL è utilizzato come reazione a qualcosa di divertente, simile a LOL", "LMAO": "lmao e utilizzato per dire che stai ridendo a crepapelle", "WDYM": "WDYM è utilizzato per chiedere ad una persona che cosa intende per quello che ha detto" }
parola = input("Scrivi una parola moderna che non capisci (usa tutte le lettere maiuscole!): ")
if parola in meme_dict.keys():
  print(meme_dict[parola])
else:
  print("Non abbiamo ancora questa parola...Ma ci stiamo lavorando!")
