```typescript
export class KoPeYkA {

    public name : string = "Artemy Vanchugov";
    public yo : string = "?";
    public city : string = "Russia, Novosibirsk";
    languages: string[] = ["Russian"];

    VKontakte: string = "https://vk.com/a.vanchugov";
    Telegram: string = "https://t.me/KoP3YkA";

    ownProjects: string[] = ["blackmanagerlite", "skyland"];
    companys: string[] = ["Abelix"];

    devLanguages: DevLanguages[] = [DevLanguages.TYPESCRIPT, DevLanguages.JAVA, DevLanguages.JAVASCRIPT, DevLanguages.PYTHON];

    constructor(action: Action = Action.SEND_ME_MESSAGE_TO_VK_OR_TG) {
       KoPeYkA.reply();
    }

}
```
