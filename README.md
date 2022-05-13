Salut ! 

Aujourd'hui je traduit un tuto en français pour le Rich Presence pour vos serveur FiveM. (Le Script a aussi était assembler)
=> Tuto de base (https://forum.cfx.re/t/how-to-updated-discord-rich-presence-custom-image/157686)

Etape 1:

- Pour commencer il vous faut aller ici => https://discord.com/developers/applications/
- Une fois sur le site en question, vous devez crée une applications

![This is an image](https://user-images.githubusercontent.com/85886066/168369151-8be3a80a-f72a-465e-9c73-e3959ac6409a.png)

- Lorsque vous créez une nouvelle application, vous verrez une page similaire à celle illustrée ci-dessous sur la photo.
- Vous devrez copier l'identifiant de l'application (voir la flèche) et l'enregistrer pour plus tard.

![This is an image](https://forum.cfx.re/uploads/default/optimized/3X/0/a/0a7854291a3546864a12b4283520bd3c58192e6f_2_690x300.png)

- Vous devez maintenant accéder à la barre de navigation de gauche et accéder à Rich Presence>Art Assets.

![This is an image](https://forum.cfx.re/uploads/default/optimized/3X/b/c/bca411d7b51bf613247873d39194255605e3e688_2_671x500.png)

- C'est là que la magie commence, ici vous pouvez télécharger votre image. (L'image doit être de 512x512 pixels ou plus)

![This is an image](https://forum.cfx.re/uploads/default/optimized/3X/c/a/cae8666cda59131cdb35a32e6802c4c31d9af5d6_2_690x407.png)

- Si vous avez téléchargé l'image, vous devrez vous souvenir du nom de l'image et n'oubliez pas de cliquer sur "Enregistrer les modifications".

![This is an image](https://forum.cfx.re/uploads/default/optimized/3X/5/1/51156ebc2414b316ba510911a7242c09a12ca097_2_690x443.png)

Nous avons maintenant l'identifiant de l'application Discord et le nom de l'image. Enfin, nous devons mettre ces valeurs dans un script.
J'ai créé un script très simple et très simple pour que vous puissiez le tester.

créez un dossier dans le dossier de ressources du serveur et appelez-le discord
créez 2 fichiers, l'un appelé fxmanifest.lua et l'autre appelé client.lua
collez le code ci-dessous dans le bon fichier
(11-11-2018) Merci à @d0p3t, nous avons maintenant 3 nouveaux natifs
Nouveaux natifs :

SetDiscordRichPresenceAssetSmall
SetDiscordRichPresenceAssetSmallText
SetDiscordRichPresenceAssetText
(26-02-2021) Merci à blattersturm 1.5k, nous avons un nouveau natif
Nouveau natif :

SetDiscordRichPresenceAction
Vérifiez le code ci-dessous pour voir comment les utiliser et ce qu'ils font !


Si vous avez suivi toutes les étapes et utilisé les connaissances courantes, vous verrez ceci :

![This is an image](https://i.gyazo.com/6c6f8b0c1956f9a5c34034eb537b1d33.png)
![This is an image](https://cdn.discordapp.com/attachments/413281791760269314/489879134336712734/2b0ddca1acba63668e52a4e798044348.png)
![This is an image](https://i.imgur.com/QtdUAVM.png)
![This is an image](https://forum.cfx.re/uploads/default/original/3X/f/5/f5efc22b42612bda36c035a6a558aa9198fb47f2.png)
![This is an image](https://forum.cfx.re/uploads/default/original/4X/5/d/d/5ddbb365a446818bf25fbafb1a07c598c2aec335.png)

you might want to leave a like :heart: if you found this post helpfull
Enjoy!
