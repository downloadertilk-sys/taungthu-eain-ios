# တောင်သူ့အိမ် MM Crop Yield Calculator v1.4 — iOS Cloud Build Project

ဤ Project တွင် လက်ရှိ v1.4 HTML ကို Capacitor ဖြင့် iOS App အဖြစ် ထည့်သွင်းရန် ပြင်ဆင်ထားသည်။ Mac မလိုဘဲ Cloud macOS Build service (ဥပမာ Codemagic) တွင် build လုပ်နိုင်သည်။

## ပါဝင်သောဖိုင်များ
- `www/index.html` — လက်ရှိ v1.4 App HTML
- `package.json` — Capacitor dependencies
- `capacitor.config.json` — App ID / App Name
- `codemagic.yaml` — Cloud build အတွက် အခြေခံ workflow

## Cloud Build အဆင့်များ
1. ZIP ကို ဖြည်ပါ။
2. Project folder ကို GitHub repository အသစ်တစ်ခုသို့ upload လုပ်ပါ။
3. Codemagic တွင် GitHub repository ကို ချိတ်ဆက်ပါ။
4. iOS workflow ကို run လုပ်ပါ။
5. iPhone ပေါ်တွင် တပ်ဆင်နိုင်သော signed IPA ထုတ်ရန် Apple Developer Program အကောင့်နှင့် signing/provisioning လိုအပ်သည်။

## သတိပြုရန်
- ဤ ZIP သည် iOS Cloud Build အတွက် source project ဖြစ်ပြီး IPA ဖိုင်မဟုတ်သေးပါ။
- Apple Account ဖန်တီးခြင်းနှင့် Developer Program enrollment မပြီးသေးသဖြင့် signed IPA ကို ယခုချက်ချင်း ထုတ်၍မရသေးပါ။
- App ID ကို Android package ID နှင့် တူညီအောင်ထားထားသည်။ Apple App Store သို့ တင်မည့်အခါ Bundle ID မထပ်စေရန် စစ်ဆေးပါ။
