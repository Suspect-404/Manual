#  التتبع وإعادة عرض المعركة - Tracker and Battle Recorder

يوجد في Project Reality: Battlefield 2 نوعان من إعادة عرض المعارك:

1: إعادة عرض ثنائية الأبعاد (2D): تعرض ساحة المعركة بالكامل من منظور علوي، وتُعرف باسم **Tracker**، وتحمل الملفات الخاصة بها الامتداد **.prdemo**.

2: إعادة عرض ثلاثية الأبعاد (3D): تتيح مشاهدة المعركة من خلال كاميرا داخل اللعبة يمكنك التحكم بها بحرية، وتُعرف باسم **Battle Recorder (BR)**، وتحمل الملفات الخاصة بها الامتداد **.bf2demo**.للحصول على ملفات إعادة العرض، يجب تنزيلها من الموقع الإلكتروني الخاص بالخادم الذي لعبت عليه. وإذا لم تعرف رابط الموقع، يمكنك طلبه عبر خادم Discord الخاص بذلك الخادم، كما تتوفر روابط جميع الخوادم في قناة **#server-hosts** على [خادم الديسكورد الرسمي لبرجوكيت ريالتي](https://discord.me/projectreality "PR:BF2 Official Discord")

توفر بعض الخوادم ملفات Tracker وBattle Recorder بطريقة سهلة الوصول، مع عرض معلومات مثل اسم الخريطة، والطبقة (Layer)، ونمط اللعب، ووقت المباراة. أما في الخوادم التي لا توفر هذه الملفات بهذه الطريقة، فإن الحصول على ملفات إعادة العرض يكون أكثر صعوبة ويتطلب خطوات إضافية.

### ## التتبع (Tracker) {#tracker}
يسهل العثور على ملف إعادة العرض الذي تبحث عنه، إذ يتضمن اسم الملف وقت المباراة، واسم الخريطة، ونمط اللعب، والطبقة (Layer). 

{% note %}
ضع في اعتبارك أن الخادم قد يستخدم منطقة زمنية مختلفة، لذلك قد يختلف التاريخ أو الوقت الظاهر في أسماء الملفات قليلًا عما تتوقعه. 
{% endnote %}

بعد تنزيل ملف بصيغة .**prdemo**، افتح [هذا الموقع](https://yossizap.github.io/realitytracker/ "Tracker Website")، ثم انقر على Choose file، واختر الملف الذي قمت بتنزيله.

مثال على عرض المعركة باستخدام Tracker:

{{ "Tracker Example" | youtube("JiBxdTpJDIA") }}

### مسجل المعارك (Battle Recorder) {#battle-recorder}
إذا لم يكن ملف Battle Recorder متوفرًا مع ملف Tracker، فسيصبح العثور على ملف إعادة العرض المطلوب أكثر صعوبة، لأن اسم ملف Battle Recorder يتضمن التاريخ فقط. لذلك، يُنصح أولًا بالعثور على ملف Tracker الخاص بالمباراة نفسها.ونظرًا لأن ملفات Battle Recorder أكبر حجمًا من ملفات Tracker، فإن الوقت الموجود في اسم ملف Battle Recorder يكون عادةً متأخرًا بحوالي خمس دقائق (زيادة أو نقصانًا قليلًا) عن الوقت الموجود في اسم ملف Tracker

After you download a .bf2demo file, you need to place it in:

```
%UserProfile%\Documents\ProjectReality\Profiles\Default\demos
```

Note that **you may have to create the 'demos' directory** manually. After the BR file is in the correct directory, you can launch the game. If the game is already running, you have to restart it — otherwise the BR file will not appear on the list. The demo can be found at **REPLAYS** in the main menu. Choose the desired file in the Battlerecorder Library section and then Play File. 

{% note %}
The game version the BR was recorded in has to match the game version you have installed in order to play it. Otherwise the game will crash with the 'Networkables already added' error.
{% endnote %}

Example of how playing Battle Recorder looks like:

{{ "BattleRecorder Example" | youtube("CMF5swC4qaw") }}

### Creating BR files {#recording}
You can also make your own recordings, but only while being in a local server. To do so open the console with **`** \(the key above Tab and left of 1\) and type:

```
demo.recorddemo file
```

where **file** will be the name of your recording. 

To stop recording type:

```
demo.stoprecording
```

In this case you will find file.bf2demo in:

```
Your PR:BF2 Installation Folder\mods\pr\Demos
```

#### Controls {#battlerecorder-controls}
When in a recording you can switch between Player Camera and Free Roam with **Right Click** or hold **T** and press the button Player Cam / Free Cam. Press **Space** to cylce between players.

Number keys \(**1-9**\) change speed, alternatively you can hold **Q** and choose the speed you want.

To raise the camera hold **Z**, to move forward fast double tap **W**. To slow down movement hold **Shift** while moving. While in Player Cam you can use your scroll wheel to zoom in and out.

To go back to the beginning of the recording you can press the **Restart** button when in the **Q** menu.

