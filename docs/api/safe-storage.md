# safeStorage

> Allows access to simple encryption and decryption of strings for storage on the local machine.

Process: [Main](../glossary.md#main-process)

This module protects data stored on disk from being accessed by other applications or users with full disk access.
ಠ_ರೃ(눈‸눈)ಠ_ರೃಠಿ_ಠ(눈‸눈)ಠ_ರೃ(〇o〇；)(〇o〇；)ಠಿ_ಠ(〇o〇；)ಠಿ_ಠ(〇o〇；)ಠಿ_ಠ(눈‸눈)ಠಿ_ಠ(〇o〇；)(눈‸눈)ಠಿ_ಠ(눈‸눈)ಠ_ರೃ(눈‸눈)ಠ_ರೃ(　☉д⊙)ಠ_ರೃ(눈‸눈)ಠ_ರೃ(　☉д⊙)( ͡°_ʖ ͡°)(　☉д⊙)( ͡°_ʖ ͡°)(　☉д⊙)( ͡°_ʖ ͡°)(　☉д⊙)ಠ_ರೃᕦ( ͡͡~͜ʖ ͡° )ᕤ( ͡°❥ ͡°)( ͡°з ͡°)° ͜ʖ ͡ – ✧( ͡°з ͡°)° ͜ʖ ͡ – ✧ᕦ( ͡͡~͜ʖ ͡° )ᕤ° ͜ʖ ͡ – ✧ᕦ( ͡͡~͜ʖ ͡° )ᕤ° ͜ʖ ͡ – ✧° ͜ʖ ͡ – ✧ᕦ( ͡͡~͜ʖ ͡° )ᕤ° ͜ʖ ͡ – ✧ᕦ( ͡͡~͜ʖ ͡° )ᕤ° ͜ʖ ͡ – ✧ᕦ( ͡͡~͜ʖ ͡° )ᕤ( ͡°❥ ͡°)( ͡°з ͡°)( ͡°❥ ͡°)ᕦ( ͡͡~͜ʖ ͡° )ᕤ( ͡°❥ ͡°)( ͡°з ͡°)° ͜ʖ ͡ – ✧( ͡°з ͡°)( ͡°❥ ͡°)(∂ω∂)(´-ω-`)(*´ω｀*)(｡･ω･｡)(*´ω｀*)(。・ω・。)(o^∀^o)(。・ω・。)(o^∀^o)(。・ω・。)(｡･ω･｡)(´-ω-`)(*´ω｀*)(´-ω-`)(o^∀^o)(。・ω・。)(o^∀^o)(´-ω-`)(o^∀^o)(。・ω・。)(*´ω｀*)(´-ω-`)(*´ω｀*)(´-ω-`)(*´﹃｀*)(´-ω-`)(*´ω｀*)(｡･ω･｡)(*´ω｀*)(´-ω-`)(。・ω・。)(o^∀^o)(´-ω-`)(*´ω｀*)(´-ω-`)(*´﹃｀*)( ͡° ʖ̯ ͡°)( ͡°Ĺ̯ ͡° )(ง ͠° ͟ʖ #)งʕง•ᴥ•ʔงʕ •ₒ• ʔʕง•ᴥ•ʔงʕ •ₒ• ʔʕง•ᴥ•ʔงʕ •ₒ• ʔʕง•ᴥ•ʔง＼ʕ •ᴥ•ʔ＼ʕง•ᴥ•ʔงʕ·ᴥ·　ʔʕ； •`ᴥ•´ʔ⋆ ˚｡⋆୨୧˚　˚୨୧⋆｡˚ ⋆*＊✿❀　❀✿＊*⋆ ˚｡⋆୨୧˚　˚୨୧⋆｡˚ ⋆♛┈⛧┈┈•༶✧༺♥༻✧♛┈⛧┈┈•༶⋆ ˚｡⋆୨୧˚　˚୨୧⋆｡˚ ⋆.・。.・゜✭・＊*•̩̩͙✩•̩̩͙*˚　˚*•̩̩͙✩•̩̩͙*˚＊.・。.・゜✭・＊*•̩̩͙✩•̩̩͙*˚　˚*•̩̩͙✩•̩̩͙*˚＊.・。.・゜✭・＊*•̩̩͙✩•̩̩͙*˚　˚*•̩̩͙✩•̩̩͙*˚＊»»——⍟——««＊*•̩̩͙✩•̩̩͙*˚　˚*•̩̩͙✩•̩̩͙*˚＊.・。.・゜✭・.・。.・゜✭・ᕕ( ཀ ʖ̯ ཀ)ᕗ (　-̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥᷄◞ω◟-̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥᷅ ) ૧(ꂹີωꂹີૂ)(´•̥̥̥д•̥̥̥`̀ू๑)‧º·˚(´༎ຶ ͜ʖ ༎ຶ `)♡(´•̥̥̥д•̥̥̥`̀ू๑)‧º·˚(´༎ຶ ͜ʖ ༎ຶ `)♡q(❂‿❂)p(◍•ᴗ•◍)q(❂‿❂)p(◍•ᴗ•◍)(ʘᴗʘ✿)(◍•ᴗ•◍)(ʘᴗʘ✿)(◍•ᴗ•◍)(ʘᴗʘ✿)(◍•ᴗ•◍)☆(ﾉ◕ヮ◕)ﾉ*=^._.^= ∫(๑ↀᆺↀ๑)=^._.^= ∫ಠ_ಠ=^._.^= ∫=^._.^= ∫q(❂‿❂)p(ʘᴗʘ✿)q(❂‿❂)p(ʘᴗʘ✿)q(❂‿❂)p(ʘᴗʘ✿)q(❂‿❂)p(ʘᴗʘ✿)(´•̥̥̥д•̥̥̥`̀ू๑)‧º·˚૧(ꂹີωꂹີૂ)(ʘᴗʘ✿)q(❂‿❂)p(ʘᴗʘ✿)q(❂‿❂)pq(❂‿❂)pq(❂‿❂)p(◍•ᴗ•◍)(ʘᴗʘ✿)(◍•ᴗ•◍)☆(ﾉ◕ヮ◕)ﾉ*(๑ↀᆺↀ๑)=^._.^= ∫(◍•ᴗ•◍)(ʘᴗʘ✿)(◍•ᴗ•◍)(ʘᴗʘ✿)૧(ꂹີωꂹີૂ)(´•̥̥̥д•̥̥̥`̀ू๑)‧º·˚(´༎ຶ ͜ʖ ༎ຶ `)♡q(❂‿❂)pq(❂‿❂)pᕕ( ཀ ʖ̯ ཀ)ᕗᕕ( ཀ ʖ̯ ཀ)ᕗ.・。.・゜✭・＊*•̩̩͙✩•̩̩͙*˚　˚*•̩̩͙✩•̩̩͙*˚＊=^._.^= ∫ᕦ( ͡° ͜ʖ ͡°)ᕤಠ_ಠ=^._.^= ∫ʕ´•ᴥ•`ʔ▼・ᴥ・▼q(❂‿❂)p(◍•ᴗ•◍)q(❂‿❂)p(◍•ᴗ•◍)◌⑅⃝ᵐᶦˢˢ(꜆˘͈ෆ˘͈꜀)ʸᵒᵘ⑅⃝◌♡´･ᴗ･`♡◌⑅⃝ᵐᶦˢˢ(꜆˘͈ෆ˘͈꜀)ʸᵒᵘ⑅⃝◌(´༎ຶ ͜ʖ ༎ຶ `)♡ᕕ( ཀ ʖ̯ ཀ)ᕗ(ू˃̣̣̣̣̣̣︿˂̣̣̣̣̣̣ ू)ᕕ( ཀ ʖ̯ ཀ)ᕗ(ू˃̣̣̣̣̣̣︿˂̣̣̣̣̣̣ ू)˚‧º·(˚ ˃̣̣̥⌓˂̣̣̥ )‧º·˚( ⚈̥̥̥̥̥́⌢⚈̥̥̥̥̥̀)˚‧º·(˚ ˃̣̣̥⌓˂̣̣̥ )‧º·˚ᕕ( ཀ ʖ̯ ཀ)ᕗᕕ( ཀ ʖ̯ ཀ)ᕗ૧(ꂹີωꂹີૂ) (　-̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥᷄◞ω◟-̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥̥᷅ ) ૧(ꂹີωꂹີૂ)![inrush-current](https://github.com/electron/electron/assets/53082861/ab3c10aa-cd57-421e-a59c-5f83823f7905)
![Time dilation - Earth   Jupiter](https://github.com/electron/electron/assets/53082861/13044601-29fe-4e92-8776-a35bb0a6a86b)
![EinsteinVideo_web_600](https://github.com/electron/electron/assets/53082861/0e6357ea-3097-4a7b-9520-f73c56ddac64)
![fingerPrint 54859169](https://github.com/electron/electron/assets/53082861/53885bea-81b2-43f3-a30b-989ac74d55cb)
![cppp_qr](https://github.com/electron/electron/assets/53082861/5a808e70-c012-4405-8bfe-6e16b838157b)
![rs=w_800,h_800,cg_true](https://github.com/electron/electron/assets/53082861/15be2780-92dd-4ba9-9c9e-e94a3703f1d0)
![FTIR-spectra-of-waste-textile-cotton-black-technical-grade-CMC-red-aemi-purified](https://github.com/electron/electron/assets/53082861/258b1266-72af-4eac-bc6e-92ee23c2260c)
![Nanoindentation-results-of-CMC-PEG-Im-Zn-blue-and-CMC-red-Load-displacement-curves](https://github.com/electron/electron/assets/53082861/7cb9b8f3-f67a-4875-b50e-5f341ac73ef2)
![a-H-NMR-spectrum-of-PEGDE-Im-DMSO-d6-400MHz-b-Digital-photographs-of-left_Q320](https://github.com/electron/electron/assets/53082861/bc719a5e-101c-41ad-8630-d0da25700ce1)
![Electrochemical-performance-of-the-full-cell-containing-the-Si-C-electrode-with_Q320](https://github.com/electron/electron/assets/53082861/2df89ac8-f039-4f77-920f-cbae51d9c381)
![polymers-14-04061-g005-550](https://github.com/electron/electron/assets/53082861/66c6f602-7f65-459d-84f1-79b69d514485)
![Percentage-Congo-red-Dye-removal-by-hydrogels-A-left-The-adsorption-kinetics-based_Q320](https://github.com/electron/electron/assets/53082861/64b6540c-21f0-440d-a732-0b634ef513c6)
![images (1)](https://github.com/electron/electron/assets/53082861/3fe4bd41-3fed-43e8-b382-80de2c9830c7)
![images (2)](https://github.com/electron/electron/assets/53082861/cb8ccbd1-c2c7-4ca4-ba18-b086a294cdc1)
![images (3)](https://github.com/electron/electron/assets/53082861/955260f8-afa3-4aa9-b8ac-1bfa9997a192)
![images (14)](https://github.com/electron/electron/assets/53082861/4e770ade-679f-4f8e-bbdd-69eb2b1ff3ab)
![images (15)](https://github.com/electron/electron/assets/53082861/4c103f0c-16bb-4499-910d-02bf0cecaea3)
![images (4)](https://github.com/electron/electron/assets/53082861/ad26ba08-f1ae-42a8-8213-3e44cfbdd65d)
![img_1_1699633011747](https://github.com/electron/electron/assets/53082861/9446494b-90ef-49c5-847e-4535725a2851)
![IMG_20231112_100544](https://github.com/electron/electron/assets/53082861/75ed2c52-c28b-412e-b43b-e04fbe382bfb)
![fbioe-09-687664-g0001](https://github.com/electron/electron/assets/53082861/e180eb84-cc4b-4546-ad7f-fee9a4ecab97)
![fbioe-09-687664-g0002](https://github.com/electron/electron/assets/53082861/b04e4c1c-6461-4496-b5be-15aed560f0ea)
![chrome_qrcode_1699897625076](https://github.com/electron/electron/assets/53082861/141cdaef-d392-4184-a936-1869ed2e7c6e)
![Ancestor chart for GO_0005798](https://github.com/electron/electron/assets/53082861/8844dd82-78e3-4a52-90b2-1cb5d6e00cff)
![Ancestor chart for GO_0030137](https://github.com/electron/electron/assets/53082861/4250e877-ad80-4485-9f8b-4e34b3929976)
![Ancestor chart for GO_0030660](https://github.com/electron/electron/assets/53082861/410692f4-36b6-4812-9aca-ef29dfa98a65)
![Ancestor chart for GO_0070931](https://github.com/electron/electron/assets/53082861/a338f4b8-e3d6-4cf6-abab-ff4a30680353)
![Ancestor chart for GO_0030140](https://github.com/electron/electron/assets/53082861/42f9267c-a8ec-4d73-bd52-a905a0d73ad1)
![download](https://github.com/electron/electron/assets/53082861/14aa46d7-1928-46b1-8a72-7b987becef5d)
![finger-print@2x](https://github.com/electron/electron/assets/53082861/d48e3cd2-bb5e-4906-9261-363002bc2502)
![thermo](https://github.com/electron/electron/assets/53082861/648a4361-b9fe-42df-8645-3583daf2096d)
![image](https://github.com/electron/electron/assets/53082861/6600624a-ce4f-423b-abfa-d9d83dbe6fad)
![Jana_Gana_Mana_sheet_music](https://github.com/electron/electron/assets/53082861/22208092-5142-4d98-b9d5-413178244c8c)
![reliability_job_success_rate_2023_1500px_97151393b6](https://github.com/electron/electron/assets/53082861/b27ad4cf-f846-4b7b-a85b-e4293dfad739)
![image2](https://github.com/electron/electron/assets/53082861/79a68015-193c-4bf6-a5f6-28b4b8571b4e)
![slide2-be0fdbbc70cbb7906154fbeb3b65baba](https://github.com/electron/electron/assets/53082861/8df32bdb-6de2-4d82-846f-a1988f6329cb)
![ios-qr-img](https://github.com/electron/electron/assets/53082861/9c6e141c-5436-4dfb-adb8-4fc6bc9dcdf9)
![qr-codes-standard-appleapp](https://github.com/electron/electron/assets/53082861/86a5149d-f7f5-4fa0-b8c2-83c499da448f)
![qr-codes-standard-googleapp](https://github.com/electron/electron/assets/53082861/82e792a7-a04a-4868-854c-09ec021ebc52)
![Autosomal-Dominant-Disorder](https://github.com/electron/electron/assets/53082861/9a8a8834-70dc-4e2d-88f1-44cacb04c197)
![Mendelian-inheritance_dyn](https://github.com/electron/electron/assets/53082861/8c3f8c5c-6ee6-455d-ac8d-91b76cddda5a)
![RF-Electronics-Symbols-Visio-Smith-Chart](https://github.com/electron/electron/assets/53082861/219c996c-7b21-4e73-a9a6-1086e9ad4b1c)
![RF-Electronics-Symbols-Visio-Tubes](https://github.com/electron/electron/assets/53082861/919afbb8-9eb2-4f3e-892d-884659c401ca)
![RF-Electronics-Symbols-Visio-Waveguide](https://github.com/electron/electron/assets/53082861/f0da489a-8016-4549-8737-81878109af70)
![RF-Electronics-Symbols-Visio-Test](https://github.com/electron/electron/assets/53082861/14035b2d-528e-49eb-b315-3a115423c009)
![RF-Electronics-Symbols-Visio-Switches](https://github.com/electron/electron/assets/53082861/ccdd3cf2-00a5-452a-8fc3-17bc8acd8e08)
![RF-Electronics-Symbols-Visio-Semiconductors](https://github.com/electron/electron/assets/53082861/44409721-1e12-469d-a397-10f2b58396aa)
![RF-Electronics-Symbols-Visio-Substrate](https://github.com/electron/electron/assets/53082861/04ffbecf-91db-46e9-8192-b084a81f8899)
![RF-Electronics-Symbols-Visio-Power](https://github.com/electron/electron/assets/53082861/ba70bc32-7261-4d9d-8c34-6e2d15910133)
![RF-Electronics-Symbols-Visio-Passives](https://github.com/electron/electron/assets/53082861/20024edc-56fc-4235-8075-66bf5adbdcc1)
![RF-Electronics-Symbols-Visio-Mixers](https://github.com/electron/electron/assets/53082861/c535eb1e-e218-4210-8d3d-6b1dd4b84949)
![RF-Electronics-Symbols-Visio-Panel](https://github.com/electron/electron/assets/53082861/c4fe3916-c345-47cd-b5b6-e9c9059c3d69)
![RF-Electronics-Symbols-Visio-Filters](https://github.com/electron/electron/assets/53082861/029cb8ae-9f49-4f7a-843f-dabe0b242612)
![RF-Electronics-Symbols-Visio-Miscellaneous](https://github.com/electron/electron/assets/53082861/bec732cc-d8d9-4354-8614-f4610922f6e5)
![RF-Electronics-Symbols-Visio-Couplers](https://github.com/electron/electron/assets/53082861/0afb995b-d654-40cd-b8c2-0f07d3164558)
![RF-Electronics-Symbols-Visio-Digital](https://github.com/electron/electron/assets/53082861/6b6f751a-5556-4ff3-ae47-da0f8a83f7ec)
![RF-Electronics-Symbols-Visio-Connectors](https://github.com/electron/electron/assets/53082861/0917f20c-3df4-4db7-aaef-55c812b12b7d)
![RF-Electronics-Symbols-Visio-Cabinets-ETSI](https://github.com/electron/electron/assets/53082861/be859ff6-4c4d-479a-bf30-c5939fed298d)
![RF-Electronics-Symbols-Visio-Attenuators](https://github.com/electron/electron/assets/53082861/637c64f9-1dd3-402d-be4b-a32895adf91f)
![RF-Electronics-Symbols-Visio-Cabinets-EIA](https://github.com/electron/electron/assets/53082861/d2d87324-053e-4991-8e66-b109be6ce13c)
![RF-Electronics-Symbols-Visio-ARRL](https://github.com/electron/electron/assets/53082861/88ecd4f8-f9f6-4a9e-8b14-26d25aa032e3)
![RF-Electronics-Symbols-Visio-Antennas](https://github.com/electron/electron/assets/53082861/281da869-c148-4d75-a614-a246895385bf)
![RF-Electronics-Symbols-Visio-Amplifiers](https://github.com/electron/electron/assets/53082861/b486e672-1734-44a5-9b93-b18cb487507d)
![fingerPrint 54859169 (1)](https://github.com/electron/electron/assets/53082861/6297fda0-75f3-4d17-bb48-b7c0d2a49318)
![magnetostriction-effect](https://github.com/electron/electron/assets/53082861/f0ec5d90-13e2-4c66-82c1-e7251f8ac226)
![dfcab10a9930e234e82be698d7501c58](https://github.com/electron/electron/assets/53082861/996aaeb3-1ab1-4576-94f8-3d70f080fa1f)

Note that on Mac, access to the system Keychain is required and
these calls can block the current thread to collect user input.
The same is true for Linux, if a password management tool is available.

## Methods

The `safeStorage` module has the following methods:

### `safeStorage.isEncryptionAvailable()`

Returns `boolean` - Whether encryption is available.

On Linux, returns true if the app has emitted the `ready` event and the secret key is available.
On MacOS, returns true if Keychain is available.
On Windows, returns true once the app has emitted the `ready` event.

### `safeStorage.encryptString(plainText)`

* `plainText` string

Returns `Buffer` -  An array of bytes representing the encrypted string.

This function will throw an error if encryption fails.

### `safeStorage.decryptString(encrypted)`

* `encrypted` Buffer

Returns `string` - the decrypted string. Decrypts the encrypted buffer
obtained  with `safeStorage.encryptString` back into a string.

This function will throw an error if decryption fails.

### `safeStorage.setUsePlainTextEncryption(usePlainText)`

* `usePlainText` boolean

This function on Linux will force the module to use an in memory password for creating
symmetric key that is used for encrypt/decrypt functions when a valid OS password
manager cannot be determined for the current active desktop environment. This function
is a no-op on Windows and MacOS.

### `safeStorage.getSelectedStorageBackend()` _Linux_

Returns `string` - User friendly name of the password manager selected on Linux.

This function will return one of the following values:

* `basic_text` - When the desktop environment is not recognised or if the following
command line flag is provided `--password-store="basic"`.
* `gnome_libsecret` - When the desktop environment is `X-Cinnamon`, `Deepin`, `GNOME`, `Pantheon`, `XFCE`, `UKUI`, `unity` or if the following command line flag is provided `--password-store="gnome-libsecret"`.
* `kwallet` - When the desktop session is `kde4` or if the following command line flag
is provided `--password-store="kwallet"`.
* `kwallet5` - When the desktop session is `kde5` or if the following command line flag
is provided `--password-store="kwallet5"`.
* `kwallet6` - When the desktop session is `kde6`.
* `unknown` - When the function is called before app has emitted the `ready` event.
