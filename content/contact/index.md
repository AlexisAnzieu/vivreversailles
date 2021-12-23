+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 110
background = "secondary"
form_name = "defaultContact"

title = "Nous contacter"
subtitle  = ""

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/f/xayvyrzd" #default: formspree.io
email = "mail@example.com"
button_text = "Envoyer" # defaults to theme default


[message]
  success = "Merci de nous avoir contacter!" # defaults to theme default
  error = "Votre message n'a pas pu être envoyé. Merci d'envoyer un message directement à contact@vivreversailles.org" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Prénom & Nom (obligatoire)"
  error = "Merci d'entrer votre nom" # defaults to theme default

[fields.email]
  text = "E-Mail (obligatoire)"
  error = "Merci d'entrer votre adresse email" # defaults to theme default

[fields.phone]
  text = "Quartier de Versailles ou ville (obligatoire)"
  error = "Merci d'entrer votre quartier" # defaults to theme default

[fields.message]
  text = "Qu'aimeriez-vous nous dire ?"
  error = "Merci d'entrer votre message" # defaults to theme default

  [fields.subscriptionValidated]
  text = "Qu'aimeriez-vous nous dire ?"
  error = "Merci d'entrer votre message" # defaults to theme default
+++
