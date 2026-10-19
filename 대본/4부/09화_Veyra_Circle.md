# SHIP IT — 4부 9화

## Veyra Circle (베이라 서클)

> **표기 전용 정보 (낭독하지 않음)**
> - 부/화: 4부 9화 · 서사 기능: 환자용 멤버십 앱 기획, 사용자 여정 설계, 의료정보 보호(HIPAA)·마케팅 동의(opt-in), 포인트 제도 논쟁, 앱이 의료기기가 되는 선
> - 배경: 8화 3주 뒤 화요일 오전 9시 ~ 오후 3시, Veyra 제품 회의실(벽에 사용자 여정 지도) → 오후 3시 복도
> - 등장인물: Nina Park(신임 프로덕트 매니저, 전직 헬스케어 앱 PM), Zoe, Elena, Diane, Noah, Marcus, Ava(후반 전화)
> - 비즈니스 스킬: 제품 기획(사용자 여정·MVP), 개인정보·동의 논의, 기능 우선순위 정하기, 원칙에 따라 기능 빼기
> - 난이도: B2 · 턴 수: 120 (도입 15 · 장면1 35 · 장면2 30 · 절정·전환 25 · 마무리 15)
> - 규칙: 지문 없음. 전 화 100% 「화자명: 대사」. 1턴 15단어 이내 + 긴 턴 10~15회(25~35단어).
> - 복선 설치: **Nina Park 합류** · 앱 첫 화면 = "When to call your injector" 경고 신호 + 응급 버튼(시술자 → 911) · **진단 기능 금지 — 진단하면 앱 자체가 의료기기(Diane)** · 마케팅 동의는 별도·기본 해제(opt-in) · 데이터 판매 금지·최소 수집·사진 삭제권 · **포인트 제도 기각: "We don't gamify needles."** · 보상은 교육·사후 관리 알림 중심 · Zoe "When we sell something that isn't a needle…"(→5부 6화 Recover) · MVP 10주·$220K · **Ava: Dr. Pierce가 Veyra 관련 글 게시, 4천 공유**(→10화)

---

## 대본

### 도입 — 오전 9시, 사용자 여정 지도

NOAH: Everyone, meet Nina Park. Our first product manager. She built a diabetes app.

NINA: Two million users. And three privacy lawyers. I learned a lot from both.

DIANE: Only three? You were lucky.

NINA: This wall is Jess's journey. Before, during, and after treatment.

ZOE: You read my persona!

NINA: Twice. Jess is great. But she disappears after day one.

ELENA: That's when the real questions start. Swelling. Bruising. Worry.

NINA: And mostly at night, when the clinic is closed. She feels a little swelling, searches online, finds the worst possible story, and panics. Nobody is there to tell her it's normal.

MARCUS: So the app is for nights?

NINA: For the fourteen days after. And the twelve months until the next visit.

ZOE: And for loyalty. Jess comes back to the same injector. With Veyra.

ELENA: Safety first, loyalty second, in that order, please. If the app keeps Jess safe, she'll come back on her own. If it only chases loyalty, she'll feel sold to.

NINA: Agreed. Let's walk the journey. Day zero first.

NOAH: What's the goal for today?

NINA: An MVP. The smallest version that helps Jess. Ten weeks to build.

### 장면1 — 사용자 여정: 시술 후 14일

NINA: Day zero. Jess leaves the clinic. Her injector gives her a QR code.

ZOE: She scans it. Downloads Veyra Circle. Welcome screen.

NINA: What's on the first screen? This is the most important decision.

ZOE: Her before photo. And "Welcome to the Circle." With confetti.

ELENA: No. The first screen is warning signs, when to call your injector. If something goes wrong, it usually happens early, so that's when Jess needs the information most.

ZOE: Warning signs? On a welcome screen? That's terrifying.

ELENA: It's honest. Pain that gets worse. Skin turning white or blue. Vision changes.

NINA: What if we design it calmly? Not red. Not scary. Just clear.

ZOE: "Normal" and "Call now." Two columns. Swelling is normal. White skin is not.

ELENA: Yes. That I can live with. Jess needs to know what's normal too.

NINA: And a button. "Call my injector." One tap.

ELENA: And if the injector doesn't answer?

NINA: Second button. "Call 911." Or go to the nearest ER.

NOAH: My sister didn't have that. She waited two hours to call anyone. If she'd had one button in her hand, those two hours could have been ten minutes.

ELENA: Then that's the most important button in the app.

NINA: What about a symptom checker? Jess uploads a photo. The app says "normal" or not.

DIANE: Stop there, Nina. If the app diagnoses anything, even just normal or not normal, the app itself becomes a medical device. And that changes our whole timeline and budget.

NINA: Software as a medical device. I know. We avoided that at my last job.

MARCUS: What happens if we become a device?

DIANE: FDA review. Clinical validation. Another year. Maybe two.

NOAH: Then no diagnosis. General information only. And "call your injector."

ELENA: Better medically too. A photo can't feel pain. Jess can.

NINA: Day one to fourteen. Daily check-ins. Short tips. "Ice today." "Avoid the gym."

ZOE: And a day-fourteen photo? To see the result?

NINA: Optional. Stored privately. Jess can delete it any time.

ELENA: And we never use it. Not for marketing. Not without new consent.

ZOE: Linda taught us that. Separate consent. In writing.

NINA: Then month three, six, nine. Gentle reminders. "How do you feel about your result?"

ZOE: And month eleven. "Time to book your next visit."

ELENA: With her injector. Not with "any Veyra clinic."

NOAH: Why does that matter?

ELENA: Because the same injector knows her face, her history, and exactly what was injected last time. A new injector starts from zero. In medicine, continuity is safety.

NINA: Continuity is also retention. Elena, you just made Zoe happy.

ZOE: Very happy.

NINA: Good. Now the hard part. Data.

### 장면2 — 데이터와 동의

DIANE: First question. Are we covered by HIPAA?

NINA: Depends. If clinics send us patient records, we're a business associate.

MARCUS: And if they don't?

NINA: If Jess enters her own data, HIPAA may not apply, because we're not her doctor. But that doesn't mean we're free. Other laws still apply, and they're getting stricter.

DIANE: The FTC. State privacy laws. And common sense.

ELENA: Treat it like protected health information anyway. Always.

NINA: Agreed. Encrypted. Minimal. We collect only what Jess needs.

ZOE: What about her email? For marketing?

NINA: Separate consent. A checkbox. Unchecked by default. Opt-in only.

ZOE: Unchecked? Nobody checks boxes. We'll lose eighty percent.

DIANE: Then earn the twenty percent. People who choose to hear from us actually want to. Pre-checked boxes might look good on a dashboard, but they're a lawsuit waiting to happen.

NINA: At my last company, opt-in users opened emails three times more. Quality over quantity.

ZOE: Three times? …Okay. I can sell that to myself.

MARCUS: Do we ever sell the data? Even anonymized?

NOAH: Never. Write it on the first page. "We don't sell your data."

DIANE: In plain English. Not legal English.

NINA: Privacy policy at an eighth-grade reading level. I've done it before.

NOAH: Like our consent forms in the trial. Rachel loved them.

ELENA: And deletion. One button. "Delete my account and all my data."

ZOE: One button to leave? That's so easy.

NINA: It should be easy. Think about it from Jess's side. If leaving is hard, people don't trust joining. If leaving is one tap, joining feels safe, and they usually stay.

MARCUS: What about a data breach? Who's responsible?

DIANE: We are. Notification within days. Not weeks. It's in the rules.

NINA: That's why minimal data matters. You can't leak what you don't have.

NOAH: Good. Privacy by design. Not as a patch.

ZOE: Now can we talk about the fun part? Rewards.

ELENA: I've been dreading this.

ZOE: Points. Jess earns points for every treatment. Points mean discounts.

MARCUS: Points for referrals too? And for reviews?

ELENA: No. Absolutely not.

### 절정·전환 — 포인트 논쟁

ZOE: Elena, every beauty brand has points. Lumaderm has points.

ELENA: Then Lumaderm rewards people for more needles. We won't.

ZOE: It's not "more needles." It's loyalty.

ELENA: Points for treatments push people to treat sooner, or treat more, just to get a discount. But when to inject is a medical decision, and a loyalty program shouldn't be making it.

NINA: Can I add data? Our diabetes app had rewards. For logging insulin.

ZOE: See? Rewards in health apps!

NINA: Rewards for healthy behavior, like logging insulin every day. Not for buying more insulin. That's the whole difference. We rewarded what kept patients well, not what made us money.

ZOE: …That's a good point.

DIANE: And reviews for points? Incentivized reviews. The FTC hates them.

NINA: Referral rewards for medical treatment? Some states restrict them. It's messy.

NOAH: Here's the thing. What behavior do we want to reward?

ELENA: Following aftercare. Calling when something feels wrong. Coming back to the same injector.

ZOE: Those aren't sexy.

NINA: But they're useful. And they build trust. Trust is sexy. Eventually.

NOAH: Decision. No points for treatments. No points for reviews. No referral cash.

ZOE: So no rewards at all?

NOAH: Rewards for learning. Finish the aftercare guide, get a free skincare sample.

ELENA: A sample that isn't a needle. I can live with that.

NINA: We don't gamify needles. Zoe, write that on the wall.

ZOE: Fine, I give up on points for now. But one day, we'll sell something that isn't a needle, and when that happens, I want points. Lots of them.

ELENA: Skincare? Aftercare cream?

ZOE: Maybe. Something for recovery. I've been sketching.

NOAH: Not this year. One product. Do it well. Then the next one.

MARCUS: Budget for the MVP?

NINA: Two hundred twenty thousand. Ten weeks. A small agency plus me.

### 마무리 — 오후 3시, 복도

MARCUS: Approved. But I want the privacy page reviewed by Diane. Line by line.

DIANE: Already planned. In big letters.

NINA: First version: warning signs, call buttons, daily tips, reminders, deletion. That's it.

ZOE: That's very… responsible.

NINA: Responsible is a feature, especially in health. Users can't see our privacy rules or our careful design, but they can feel them. That's what makes them stay.

NOAH: Nina, welcome. You fit in already.

NINA: You fight a lot. But nicely. I like it.

ZOE: Noah. Your phone. It's Ava. Third call.

AVA: Noah, sorry. It's Dr. Pierce. He posted something. About us.

NOAH: What kind of something?

AVA: It's a long post, with a video. Four thousand shares in two hours, and it's still climbing. The comments are coming in faster than I can read them.

ELENA: Alan. He took module four in March. He beat Cole's time.

NOAH: Is it bad?

AVA: The title is "The Filler That Sells You a Fire Exit."

ZOE: Everyone. Big conference room. Now.

---

## 학습 부록

### ① 핵심 표현 10

| # | 표현 | 뜻 | 대본 속 쓰임 / 비즈니스 활용 |
|---|---|---|---|
| 1 | user journey | 사용자 여정 | 도입. 고객이 제품을 경험하는 전 과정을 시간 순으로 그린 지도. |
| 2 | MVP (minimum viable product) | 최소 기능 제품 | 도입. 핵심 문제를 푸는 가장 작은 버전. |
| 3 | This is the most important decision. | 이게 가장 중요한 결정이다. | 장면1. 회의 초점을 잡아 주는 표현. |
| 4 | If the app diagnoses, the app becomes a medical device. | 앱이 진단하면 의료기기가 된다. | 장면1. 디지털 헬스 규제의 핵심 경계. |
| 5 | Continuity is safety. | 연속성이 곧 안전이다. | 장면1. 같은 의료진에게 돌아오는 것의 가치. |
| 6 | opt-in / unchecked by default | 옵트인 / 기본 해제 | 장면2. 마케팅 수신 동의의 원칙. |
| 7 | Quality over quantity. | 양보다 질. | 장면2. 동의율이 낮아도 반응이 좋은 사용자의 가치. |
| 8 | If leaving is hard, people don't trust joining. | 떠나기 어려우면 가입을 믿지 않는다. | 장면2. 탈퇴·삭제 설계 원칙. |
| 9 | privacy by design | 설계 단계부터의 개인정보 보호 | 장면2. 나중에 덧붙이지 않고 처음부터 설계하기. |
| 10 | What behavior do we want to reward? | 어떤 행동에 보상하고 싶은가? | 절정·전환. 보상 제도 설계의 출발 질문. |

### ② 비즈니스 컬처 노트 — 헬스 앱과 개인정보
미국에서 **HIPAA**는 병원·보험사 같은 "적용 대상 기관"과 그 **업무 협력자(business associate)**에게 적용된다. 환자가 직접 입력한 데이터는 HIPAA 밖일 수 있지만, **FTC 규정과 주 개인정보법**이 적용되므로 건강 정보처럼 다루는 것이 안전하다. 마케팅 수신 동의는 **별도·기본 해제(opt-in)**가 원칙이며, 미리 체크된 박스는 분쟁 소지가 크다. 앱이 증상을 **진단**하면 **의료기기 소프트웨어(SaMD)**로 FDA 규제를 받을 수 있다. 또한 리뷰에 보상을 주는 **보상성 리뷰**는 FTC의 감시 대상이고, 의료 시술 추천에 대한 금전 보상은 주마다 규정이 다르다.

### ③ 실무 템플릿 — Veyra Circle MVP 기능 정의

| 우선순위 | 기능 | 포함 여부 | 이유 |
|---|---|---|---|
| P0 | First screen: "Normal" vs. "Call now" warning signs | ✅ | Safety first |
| P0 | Buttons: "Call my injector" → "Call 911 / nearest ER" | ✅ | Lily waited two hours |
| P0 | Delete account & all data (one button) | ✅ | Trust |
| P1 | Day 1–14 daily tips & check-ins | ✅ | Aftercare |
| P1 | Month 3/6/9/11 reminders (same injector) | ✅ | Continuity is safety |
| P1 | Optional private day-14 photo (deletable, never used for marketing) | ✅ | Patient value |
| P2 | Marketing emails (separate opt-in, unchecked) | ✅ | Quality over quantity |
| ✗ | Photo symptom checker / diagnosis | ❌ | Would become a medical device |
| ✗ | Points for treatments / reviews / referrals | ❌ | "We don't gamify needles." · FTC · state rules |
| ✗ | Selling data (even anonymized) | ❌ | "We don't sell your data." |

> **Budget:** $220K · **Timeline:** 10 weeks · **Reward:** finish aftercare guide → free skincare sample

### ④ 긴 발화 분석

> **ELENA (절정·전환):** "Points for treatments push people to treat sooner, or treat more, just to get a discount. But when to inject is a medical decision, and a loyalty program shouldn't be making it."

| 구조 | 영어 | 기능 |
|---|---|---|
| ① 문제(행동 결과) | Points for treatments push people to treat sooner, or treat more, | 제안된 기능이 사용자 행동을 어떻게 바꾸는지 지적 |
| ② 동기 폭로 | just to get a discount. | just to로 그 행동의 '잘못된 이유'를 드러냄 |
| ③ 원칙(But) | But when to inject is a medical decision, | 대비 접속사로 지켜야 할 원칙을 세움 |
| ④ 결론(누가 결정할 수 없는가) | and a loyalty program shouldn't be making it. | 결정 주체가 틀렸다는 것으로 반대를 마무리 |

**활용 패턴:** X pushes people to A, just to B → But C is a ___ decision → and X shouldn't be making it.
**연결 표현:** push people to(~하도록 밀다) · just to(단지 ~하려고) · shouldn't be making it(그 결정을 내려선 안 된다)
**연습:** 영업 인센티브가 고객에게 불필요한 업그레이드를 권하게 만드는 상황에서, 같은 구조로 반대 의견을 30단어 안팎으로 말해 보기.

---

## 한국어 번역

### 도입 — 오전 9시, 사용자 여정 지도

노아: 여러분, 니나 박을 소개할게요. 우리 첫 프로덕트 매니저예요. 당뇨 앱을 만들었어요.

니나: 사용자 200만. 그리고 개인정보 변호사 셋. 양쪽에서 많이 배웠어요.

다이앤: 셋뿐이에요? 운이 좋았네요.

니나: 이 벽은 제스의 여정이에요. 시술 전, 중, 후.

조이: 제 페르소나 읽었네요!

니나: 두 번이요. 제스는 훌륭해요. 하지만 첫날 이후 사라져요.

엘레나: 진짜 질문은 그때부터 시작돼요. 부기. 멍. 걱정.

니나: 그리고 주로 밤에요. 병원이 닫혔을 때. 조금 부은 걸 느끼고, 온라인을 검색하고, 최악의 이야기를 찾아내고, 공황에 빠지죠. 그게 정상이라고 말해 줄 사람이 아무도 없어요.

마커스: 그럼 앱은 밤용이야?

니나: 시술 후 14일을 위한 거예요. 그리고 다음 방문까지 12개월.

조이: 그리고 충성도를 위한 거죠. 제스가 같은 시술자에게 돌아오게. 베이라와 함께.

엘레나: 안전이 먼저, 충성도는 두 번째, 그 순서로 부탁해요. 앱이 제스를 안전하게 지켜 주면 그녀는 알아서 돌아와요. 충성도만 좇으면 물건을 강매당하는 기분이 들 거예요.

니나: 동의해요. 여정을 따라가 보죠. 0일 차부터.

노아: 오늘 목표는요?

니나: MVP. 제스를 돕는 가장 작은 버전. 10주 안에 만들 수 있는.

### 장면1 — 사용자 여정: 시술 후 14일

니나: 0일 차. 제스가 병원을 나서요. 시술자가 QR 코드를 줘요.

조이: 스캔해요. 베이라 서클을 다운로드. 환영 화면.

니나: 첫 화면엔 뭐가 있어요? 이게 가장 중요한 결정이에요.

조이: 그녀의 비포 사진. 그리고 "서클에 오신 걸 환영해요." 꽃가루와 함께.

엘레나: 아니요. 첫 화면은 경고 신호, 시술자에게 전화해야 할 때예요. 문제가 생긴다면 보통 초기에 생기니까, 제스에게 그 정보가 가장 필요한 때가 바로 그때예요.

조이: 경고 신호요? 환영 화면에? 무섭잖아요.

엘레나: 정직한 거예요. 악화되는 통증. 하얗거나 파랗게 변하는 피부. 시야 변화.

니나: 차분하게 디자인하면 어때요? 빨강 말고. 무섭지 않게. 그냥 명확하게.

조이: "정상"과 "지금 전화." 두 칸. 부기는 정상. 하얀 피부는 아님.

엘레나: 네. 그건 받아들일 수 있어요. 제스는 뭐가 정상인지도 알아야 해요.

니나: 그리고 버튼. "내 시술자에게 전화." 한 번 탭.

엘레나: 시술자가 안 받으면요?

니나: 두 번째 버튼. "911에 전화." 아니면 가까운 응급실로.

노아: 제 동생한텐 그게 없었어요. 누구한테 전화하기까지 두 시간을 기다렸어요. 손에 버튼 하나만 있었어도, 그 두 시간이 10분이 될 수 있었을 거예요.

엘레나: 그럼 그게 앱에서 가장 중요한 버튼이네요.

니나: 증상 체크 기능은요? 제스가 사진을 올리면. 앱이 "정상"인지 말해 줘요.

다이앤: 거기서 멈춰요, 니나. 앱이 뭔가를 진단하면, 그게 정상인지 아닌지뿐이라도, 앱 자체가 의료기기가 돼요. 그러면 일정과 예산이 통째로 바뀌어요.

니나: 의료기기 소프트웨어. 알아요. 전 직장에서 그걸 피했어요.

마커스: 우리가 기기가 되면 어떻게 되는데?

다이앤: FDA 심사. 임상 검증. 1년 더. 어쩌면 2년.

노아: 그럼 진단은 없어요. 일반 정보만. 그리고 "시술자에게 전화."

엘레나: 의학적으로도 더 나아요. 사진은 통증을 못 느끼지만. 제스는 느끼니까요.

니나: 1일부터 14일. 매일 체크인. 짧은 팁. "오늘은 얼음찜질." "헬스장 피하기."

조이: 그리고 14일 차 사진? 결과 보려고?

니나: 선택 사항. 비공개 저장. 제스가 언제든 삭제 가능.

엘레나: 그리고 우린 절대 쓰지 않아요. 마케팅에도. 새 동의 없이는.

조이: 린다가 가르쳐 줬죠. 별도 동의. 서면으로.

니나: 그다음 3개월, 6개월, 9개월. 부드러운 알림. "결과에 대해 어떻게 느끼세요?"

조이: 그리고 11개월. "다음 방문을 예약할 때예요."

엘레나: 그녀의 시술자에게요. "아무 베이라 병원"이 아니라.

노아: 그게 왜 중요해요?

엘레나: 같은 시술자는 그녀의 얼굴, 병력, 그리고 지난번에 정확히 뭘 주입했는지 알거든요. 새 시술자는 0부터 시작해요. 의료에선 연속성이 곧 안전이에요.

니나: 연속성은 유지율이기도 해요. 엘레나, 방금 조이를 행복하게 해 줬네요.

조이: 아주요.

니나: 좋아요. 이제 어려운 부분. 데이터.

### 장면2 — 데이터와 동의

다이앤: 첫 질문. 우리가 HIPAA 적용 대상인가요?

니나: 경우에 따라요. 병원이 환자 기록을 보내면 우린 업무 협력자예요.

마커스: 안 보내면?

니나: 제스가 직접 데이터를 입력하면, 우리가 그녀의 의사가 아니니까 HIPAA는 적용 안 될 수도 있어요. 그렇다고 자유로운 건 아니에요. 다른 법은 여전히 적용되고, 점점 더 엄격해지고 있어요.

다이앤: FTC. 주 개인정보법. 그리고 상식.

엘레나: 어쨌든 보호 대상 건강 정보처럼 다뤄요. 항상.

니나: 동의해요. 암호화. 최소한으로. 제스에게 필요한 것만 수집해요.

조이: 그녀의 이메일은요? 마케팅용으로?

니나: 별도 동의. 체크박스. 기본은 해제. 옵트인만.

조이: 해제 상태로요? 아무도 체크 안 해요. 80퍼센트를 잃을 거예요.

다이앤: 그럼 20퍼센트를 얻어 내요. 스스로 연락받기를 선택한 사람들은 진짜로 원하는 거예요. 미리 체크된 박스는 대시보드에선 좋아 보일지 몰라도, 소송을 기다리는 거예요.

니나: 전 회사에선 옵트인 사용자가 이메일을 세 배 더 열었어요. 양보다 질.

조이: 세 배요? …좋아요. 그건 저 자신한테 팔 수 있겠네요.

마커스: 데이터를 팔기도 해? 익명화해서라도?

노아: 절대요. 첫 페이지에 써요. "우리는 당신의 데이터를 팔지 않습니다."

다이앤: 쉬운 영어로. 법률 영어 말고.

니나: 중학교 2학년 수준의 개인정보 처리방침. 해 봤어요.

노아: 임상 때 우리 동의서처럼요. 레이첼이 좋아했죠.

엘레나: 그리고 삭제. 버튼 하나. "내 계정과 모든 데이터 삭제."

조이: 떠나는 버튼이 하나라고요? 너무 쉬운데요.

니나: 쉬워야 해요. 제스 입장에서 생각해 봐요. 떠나기 어려우면 가입을 믿지 않아요. 떠나는 게 한 번 탭이면 가입이 안전하게 느껴지고, 오히려 대개 남아요.

마커스: 데이터 유출은? 누가 책임져?

다이앤: 우리가요. 며칠 안에 통보. 몇 주가 아니라. 규정에 있어요.

니나: 그래서 최소 수집이 중요해요. 갖고 있지 않은 건 유출할 수 없죠.

노아: 좋아요. 설계 단계부터 개인정보 보호. 땜질 말고.

조이: 이제 재밌는 부분 얘기해도 돼요? 보상.

엘레나: 이거 두려워하고 있었어요.

조이: 포인트. 제스가 시술할 때마다 포인트를 쌓아요. 포인트는 할인이 되고요.

마커스: 추천에도 포인트? 그리고 리뷰에도?

엘레나: 안 돼요. 절대로.

### 절정·전환 — 포인트 논쟁

조이: 엘레나, 모든 뷰티 브랜드에 포인트가 있어요. 루마덤도 있어요.

엘레나: 그럼 루마덤은 더 많은 바늘에 보상하는 거죠. 우린 안 해요.

조이: "더 많은 바늘"이 아니에요. 충성도예요.

엘레나: 시술 포인트는 할인을 받으려고 더 빨리, 더 많이 시술하도록 사람들을 밀어요. 하지만 언제 주입할지는 의학적 결정이고, 그걸 로열티 프로그램이 내려선 안 돼요.

니나: 데이터를 보태도 될까요? 우리 당뇨 앱에 보상이 있었어요. 인슐린 기록에.

조이: 봤죠? 헬스 앱에 보상!

니나: 건강한 행동에 대한 보상이었어요. 매일 인슐린을 기록하는 것 같은. 인슐린을 더 사는 것에 대해서가 아니라요. 그게 차이의 전부예요. 우린 돈 버는 행동이 아니라 환자를 건강하게 지키는 행동에 보상했어요.

조이: …좋은 지적이네요.

다이앤: 그리고 포인트 받는 리뷰? 보상성 리뷰. FTC가 싫어해요.

니나: 의료 시술 추천 보상이요? 일부 주는 제한해요. 복잡해요.

노아: 중요한 건요. 어떤 행동에 보상하고 싶은 거죠?

엘레나: 사후 관리 따르기. 이상하면 전화하기. 같은 시술자에게 돌아오기.

조이: 그건 섹시하지 않잖아요.

니나: 하지만 유용해요. 그리고 신뢰를 쌓죠. 신뢰는 섹시해요. 결국엔.

노아: 결정. 시술에 포인트 없음. 리뷰에 포인트 없음. 추천 현금 없음.

조이: 그럼 보상은 아예 없어요?

노아: 배움에 대한 보상. 사후 관리 가이드를 끝내면 스킨케어 샘플 무료.

엘레나: 바늘이 아닌 샘플. 그건 받아들일 수 있어요.

니나: 우린 바늘을 게임으로 만들지 않는다. 조이, 그거 벽에 써요.

조이: 좋아요, 포인트는 일단 포기할게요. 하지만 언젠가 바늘이 아닌 걸 팔게 될 거예요. 그때가 오면 포인트를 원해요. 아주 많이요.

엘레나: 스킨케어? 사후 관리 크림?

조이: 어쩌면요. 회복을 위한 뭔가. 스케치하고 있었어요.

노아: 올해는 아니에요. 제품 하나. 잘하고. 그다음에.

마커스: MVP 예산은?

니나: 22만 달러. 10주. 작은 에이전시 하나에 저.

### 마무리 — 오후 3시, 복도

마커스: 승인. 하지만 개인정보 페이지는 다이앤이 한 줄씩 검토하길 원해.

다이앤: 이미 계획했어요. 큰 글씨로.

니나: 첫 버전: 경고 신호, 전화 버튼, 매일 팁, 알림, 삭제. 그게 다예요.

조이: 아주… 책임감 있네요.

니나: 책임감이 기능이에요. 특히 건강 분야에선요. 사용자들은 우리 개인정보 규칙이나 신중한 설계를 볼 순 없지만, 느낄 순 있어요. 그게 그들을 머물게 하죠.

노아: 니나, 환영해요. 벌써 잘 어울리네요.

니나: 많이 싸우시네요. 하지만 친절하게. 좋아요.

조이: 노아. 전화요. 에이바예요. 세 번째 전화.

에이바: 노아, 죄송해요. 피어스 선생님이요. 뭔가 올렸어요. 우리에 대해.

노아: 어떤 뭔가요?

에이바: 영상이 달린 긴 글이에요. 두 시간 만에 공유 4천, 아직도 올라가고 있어요. 댓글이 제가 읽는 것보다 빨리 달려요.

엘레나: 앨런. 3월에 모듈 4를 들었는데. 콜의 기록을 깼고요.

노아: 나빠요?

에이바: 제목이 "비상구를 파는 필러"예요.

조이: 다들. 대회의실. 지금.
