# leikjaforritun

1. Game loop er mjög mikilvægur partur af öllum leikjum. Game loop er loop sem sér um process input, update og render.
Process input skynjar þegar ýtt er á takka á lyklaborðinu og smellt á músina. Update uppfærir leikinn samkvæmt fps(Hversu hratt game loop run-ar ).
Render teiknar allt saman á skjáinn. Game loop-an er alltaf í gangi meðan maður spilar leikinn þótt maður sé ekki að gera neitt, 
game loop-an sér til dæmis líka um grafík og tónlist.

2. Leikjavélar eru forrit sem koma með allskonar innbyggðum tólum sem gerir forriturum kleift að gera leiki harðar og betur.

Unity: Unity er leikjavél sem var gerð af Unity technologies og gefin út 2005. Unity notar forritunar málið C# og Javascript.
Unity gerir forriturum kelift að gera bæði 2D og 3D leiki. Unity getur byggt leiki fyrir 27 platforms(Windows, macOS, linux til dæmis).

Unreal: Unreal er leikjavél sem var gerð af Epic games og var gefin út 1998. Unreal notar forritunarmálið C++. Unreal er þekkt fyrir góða grafík.
Unreal getur byggt leiki á mörgum platforms eins og til dæmis Windows, macOS og Nintendo Switch .

3. Collision detection gæti verið úfært þannig að hver hlutur í leiknum hefur hitbox,
ef byssukúla eða eitthvað annað fer í hitboxið hjá characternum missir hann líf eða deyr.

if player() collide with mob():
 die()

4. Assets er allt sem spilarinn getur séð, heyrt, og interactað við. til dæmis Character modelinn, hljóðinn og missionin.

5. Game objects eru hlutir í leiknum sem þú getur tengt components við, Game objects gera ekki mikið
annað en að halda utan um öll componentinn sem þú tengir við game objectið. 

6. Prefabs eru endurnotanleg copy's af Game objectum convertað yfir í asset.

7. 

8. Tags eru gildi sem þú tengir við game objectana, layers eru aðallega notaðir af myndavélum til að sýna bara ákveðinn part af senunni.

