# Student Project README

*A Korean version follows below. 한국어 안내는 문서 아래쪽에 있습니다.*

**Concept Explorer** — the tool you will use in the weekly ontologizing sessions of
*Solving a Valuable Business Problem Using Foundational AI Ideas*.

**Open the tool:** https://phenomenaldatalab.github.io/Foundations-of-AI-for-Business/

---

## The workspace

**The board (left).** Sketch how your concepts relate. Drop concepts on it, connect them
with arrows, draw and annotate freely.

**Your ontology (right).** The concept list itself, organised four ways:

| Tab | What it is for |
| --- | --- |
| **Raw** | Every concept you are working with, in one flat list |
| **Categories** | The same concepts sorted into the course's concept types |
| **Causal** | An outline of what causes what. `Tab` indents, `Shift+Tab` outdents |
| **Table(editing)** | The ontology editor, one column per concept type |

**Notes (bottom).** Free space for anything: your contrarian belief, questions for the
instructor, what you want to test next.

A **node on the board is a concept**. Renaming it on the board or in the list updates both
simultaneously. Anything you sketch with **+ Concept** joins the concept list automatically.
**Text** is not collected into the list, so use it freely to sketch your idea.

## The concept types

Everyone starts from the same six types, taken from the course framework:

**Assumptions** · **Problem-solving processes** · **Representation** · **Aggregation** ·
**Outcomes** · **Context**

Inside any type you can create your own **subtypes** with **⊞**, for example, by level of
abstraction. You can also adapt the types themselves: click the coloured dot to change a
colour, click the name to rename, **✕** removes a type you never use.

Every node on the board takes the colour of its type, so the board stays readable as it
fills up. To change a node's type, select it and use the type menu at the bottom of the board.

## Weekly routine

1. Open the link. Your work from last week is already there.
2. Add, rename, delete, recategorise, sketch, connect.
3. **Before you close the tab, press `Save version`.** It is named for you (Session 1,
   Session 2, …), and you can rename it by clicking the name. This snapshot is what you
   hand in for the week.

`Versions` lists every snapshot you have saved, with what was in it. You can restore an
older one at any time. Your current work is backed up automatically first, so restoring
is never destructive.

## Submission

Each snapshot in the `Versions` panel has two export buttons:

- **⤓ Excel** — the ontology table, causal view, concept list, board connections and notes
- **⤓ PNG** — the board exactly as it looked in that snapshot

The buttons at the top (`PNG`, `Word`, `Excel`) do the same for whatever is on screen right now.

## Saving and backup

Your work is saved automatically, in **this browser on this computer**. Nothing is uploaded
anywhere. The timestamp at the top right (`saved 14:32`) confirms the last save.

That means:

- **Use the same browser every week.** Work saved in Chrome will not appear in Safari.
- **Private / incognito windows lose everything** when you close them.
- Clearing your browsing data clears your work too.

So once in a while, press **Backup** and keep the `.json` file somewhere safe. **Restore file**
brings it back on any computer, in any browser. Do this before the midterm and before the
final submission at the very least.

## Troubleshooting

**The export buttons are greyed out and the top says "preview mode".**
The page is open inside a preview frame, which blocks downloads. Open the link in its own
browser tab.

**Chrome asks "this site is trying to download multiple files".**
Allow it. It is safe — it just means you exported more than one file.

**My exported file is called `student_...` instead of my name.**
Filenames are restricted to English letters and numbers, because some browsers discard a
filename containing other characters. Your real name is inside the document. Typing your
name in Latin letters, or using your student ID, gives you a tidier filename.

**"⚠ not saved in browser" in red.**
The browser is refusing to store anything — usually a private window, or storage is full.
Press **Backup** now so you do not lose the session, then switch to a normal window.

**If you have any other problems with the system, please contact to TA(nie1357@kaist.ac.kr).**

---

## For maintainers

The whole tool is a single file, `index.html`. No build step, no dependencies, no server.
Edit it and commit; GitHub Pages redeploys on its own.

The instructor's concept list goes in the `SAMPLE` array near the top of the `<script>`,
as `["<typeId>", "<subtype name or empty>", "<concept>"]` triples. It ships empty, so
students start from a blank list.

Saved work is keyed to the **site**, not the page. Publishing a second copy of this tool
anywhere else under `phenomenaldatalab.github.io` would make the two share one set of
student data, so keep it to this one deployment.

---

# 학생 프로젝트 안내 (Korean)

**Concept Explorer** — *Foundations of AI for business*
수업의 학생 프로젝트에서 사용하는 도구입니다.

**바로 열기:** https://phenomenaldatalab.github.io/Foundations-of-AI-for-Business/

## 화면 구성

**보드 (왼쪽).** 개념들이 서로 어떻게 연결되는지 그려보는 공간입니다. 개념을 끌어다 놓고,
화살표로 잇고, 자유롭게 그리거나 메모할 수 있습니다.

**온톨로지 (오른쪽).** 개념 목록 자체이며, 네 가지 방식으로 볼 수 있습니다.

| 탭 | 용도 |
| --- | --- |
| **Raw** | 지금 다루고 있는 모든 개념을 목록으로 |
| **Categories** | 같은 개념을 수업의 concept type별로 묶어서 |
| **Causal** | 무엇이 무엇을 기인하는지 정리. `Tab` 들여쓰기, `Shift+Tab` 내어쓰기 |
| **Table(수정중)** | 온톨로지 에디터 - 추후 설명 예정 |

**Notes (아래).** 무엇이든 적어두는 공간입니다. 관찰에 의한 통찰, 교수님께 여쭤볼 것,
다음에 검증해볼 것 등.

보드 위의 **노드는 개념 그 자체**입니다. 보드에서 이름을 고치든 목록에서 고치든 양쪽이 동시에
바뀝니다. **+ Concept**으로 보드에 새로 그린 것도 개념 목록에 자동으로 추가됩니다.
보드에서 **Text**는 목록에 자동으로 저장되지 않으니, 생각을 스케치할 때 사용하시면 됩니다.

## Concept types

 수업 프레임워크에서 가져온 여섯 가지 타입이 기본값으로 설정되어 있습니다.

**Assumptions** · **Problem-solving processes** · **Representation** · **Aggregation** ·
**Outcomes** · **Context**

각 타입 안에 **⊞**로 자신만의 **subtype(하위 카테고리)**을 만들 수 있습니다. 예를 들어 추상화 수준별로
나눠볼 수 있습니다. 타입 자체도 수정할 수 있습니다. 색 동그라미를 누르면 색을, 이름을 누르면
이름을 바꿀 수 있고, **✕**로 쓰지 않는 타입을 지울 수 있습니다.

보드의 모든 노드는 자기 타입의 색을 따라 개념이 많아져도 한눈에 구분되도록 만들었습니다. 노드의
타입을 바꾸려면 노드를 선택한 뒤 보드 아래쪽의 타입 메뉴를 사용할 수 있습니다.

## 매주 할 일

1. 링크를 열고, 지난 작업이 그대로 남아 있는지 확인합니다.
2. 자유롭게 개념을 추가하고, 고치고, 지우고, 분류를 바꾸고, 연결합니다.
3. **탭을 닫기 전에 `Save version`을 누르세요.** 이름은 자동으로 지정되고(Session 1,
   Session 2, …) 이름을 클릭하면 바꿀 수 있습니다. 이 저장물을 과제로 제출해주시면 됩니다(자세한 사항은 아래에 있습니다.).

`Versions`에는 저장한 모든 스냅샷이 내용 요약과 함께 남습니다. 언제든 예전 것으로 되돌릴 수
있고, 되돌리기 전에 현재 작업이 자동으로 백업되므로 잃어버릴 일은 없습니다.

## 제출

`Versions` 패널의 각 스냅샷에는 내보내기 버튼이 두 개 있습니다.

- **⤓ Excel** — 온톨로지 표, 인과 뷰, 개념 목록, 보드 연결 관계, 노트
- **⤓ PNG** — 그 스냅샷 시점의 보드 화면

상단의 `PNG`, `Word`, `Excel` 버튼은 같은 내용을 **지금 화면 상태** 기준으로 내보냅니다.

## 저장과 백업

작업은 **사용한 브라우저와 컴퓨터**에 자동으로 저장됩니다. 어디로도 전송되지
않습니다. 오른쪽 위의 `saved 14:32` 표시로 마지막 저장 시각을 확인할 수 있습니다.

따라서,

- **매주 같은 브라우저를 쓰세요.** 크롬에서 저장한 작업은 사파리에 나타나지 않습니다.
- **시크릿 창은 닫는 순간 전부 사라집니다.**
- 브라우저 인터넷 사용 기록을 지우면 작업도 함께 지워집니다.

그러니 가끔 **Backup**을 눌러 `.json` 파일을 안전한 곳에 보관해두세요. **Restore file**로
어느 컴퓨터, 어느 브라우저에서든 되살릴 수 있습니다. 적어도 중간 제출 전과 최종 제출 전에는
꼭 한 번씩 받아두세요.

## 문제가 생겼을 때

**내보내기 버튼이 회색이고 위에 "preview mode"라고 뜹니다.**
페이지가 미리보기 창 안에서 열려 있습니다. 미리보기에서는 다운로드가 막힙니다. 링크를 브라우저
탭에서 직접 여세요.

**크롬이 "이 사이트에서 여러 파일을 자동으로 다운로드하려고 함"이라고 물어봅니다.**
허용하세요. 파일을 두 개 이상 내보냈다는 뜻일 뿐 위험하지 않습니다.

**내보낸 파일 이름이 내 이름 대신 `student_...`로 나옵니다.**
파일 이름은 영문자와 숫자만 쓰도록 되어 있습니다. 그 외 문자가 들어가면 파일 이름을 통째로
버리는 브라우저가 있기 때문입니다. 실제 이름은 문서 안에 제대로 들어가 있습니다. 이름 칸에
영문 이름이나 학번을 넣으면 파일 이름이 깔끔해집니다.

**빨간색으로 "⚠ not saved in browser"가 뜹니다.**
브라우저가 저장을 거부하고 있습니다. 대개 시크릿 창이거나 저장 공간이 가득 찬 경우입니다.
작업을 잃지 않도록 지금 바로 **Backup**을 누른 뒤 일반 창으로 옮기세요.

**외의 문제에 대해서는 TA(nie1357@kaist.ac.kr)에게 연락해주세요.**
