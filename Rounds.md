## 라운드 순서

각 라운드는 다음의 4개의 페이즈로 구성됩니다:

1. 미토스 페이즈 (게임의 첫 라운드에서는 수행하지 않습니다.)
2. 조사자 페이즈
3. 적 페이즈
4. 업킵 페이즈

4개의 페이즈가 모두 끝나면 라운드가 종료되고 다음 라운드의 미토스 페이즈를 진행합니다.

## 미토스 페이즈

1. 하나의 둠 토큰을 현재의 아젠다 카드에 놓습니다.

2. 플레이(아젠다 카드와 플레이에 있는 다른 카드들)에 있는 둠 토큰의 수를 현재 아젠다 카드의 둠 수치와 비교합니다. 만일 플레이에 있는 둠 토큰의 수가 아젠다 카드의 둠 수치보다 크거나 같으면 아젠다 덱을 진행합니다. 아젠다 덱의 진행은 다음과 같습니다: 현재 플레이에 있는 모든 둠 토큰을 버리고, 현재 아젠다 카드를 뒤집어서 뒷면의 지시사항을 이행한 후 그 아젠다를 플레이에서 제거합니다. 지시사항을 수행한 후 아젠다 덱의 다음 앞면이 활성화된 아젠다 카드가 됩니다.(주의: 별도의 지시가 없다면 이때가 유일하게 아젠다가 진행되는 시점입니다.)

3. 플레이어 순서대로, 각 조사자는 인카운터 덱의 최상위카드를 집습니다. 카드의 타입에 따라 다음을 수행합니다.

 * Treachery—treachery 카드가 나오면 그 능력을 해결하고 버린 인카운터 카드 더미에 놓습니다.

 * Enemy—enemy 카드가 나오면 "Spawn-" 키워드가 없다면 카드를 집은 조사자와 대면 되어 있는 상태로 플레이에 들어옵니다. 만일 "Spawn" 지시사항이 있다면 그 지시사항에서 가르키는 곳에 나타납니다.

## 조사자 페이즈

각 조사자는 다음의 행동들 중 3번의 행동을 할 수 있으며 어떤 순서로 하는지, 몇번을 하는지는 관계없습니다.

* 자신의 덱에서 카드를 한장 집습니다.
* 리소스를 1개 얻습니다.
* 행동 트리거 능력을 사용합니다.
* 현재있는 위치의 적과 대면합니다.
* 연결되어있는 장소로 이동합니다.
* 손패에서 자산이나 이벤트 카드를 플레이합니다.
* 대면되어 있는 적을 회피하도록 시도합니다.
* 현재 장소의 적과 싸웁니다.

조사자가 하나이상의 준비 상태의 적과 대면되어 있을때 회피, 전투, "Parley(협상)" 혹은 "Resign(사임)" 설명이 있는 능력의 사용외에 다른 행동은 대면 되어 있는 적들이 조사자를 공격합니다. 이 공격은 "Attack of opportunity"라고 합니다.

더 이상 하고싶은 액션이 없는 경우 턴을 일찍 끝낼 수도 있습니다. 턴이 종료했다는 표시로 조사자의 미니 카드를 뒤집어 흑백면으로 놓습니다. 사용하지 않은 액션은 없어지며 나중을 위해 보관되지 않습니다. 각 조사자가 턴을 마친후, 적 페이즈로 진행합니다.

### 카드 집기
조사자는 자신의 덱의 가장 위에 있는 카드 하나를 손패에 넣습니다.

### 자원 얻기
조사자는 하나의 리소스 토큰을 토큰 풀에서 얻습니다.

### 행동 트리거 활성화
조사자는 자신이 조종하는 카드, 같은 장소에 있는 조우한 카드 혹은 현재의 액트, 아젠다 카드에 있는 행동 트리거 능력을 사용합니다. ([발동 능력](rulerefs/Abilities.md#trigger-abilities) 참고)

### 대면(Engage)
조사자는 현재 장소의 적 하나를 대면합니다. 적을 대면하기 위해서 조사자는 적 카드를 자신의 위협 영역으로 옮겨옵니다. [적의 대면](rulerefs/EnemyEngagement.md) 참고

전략 팁: 이 행동으로 현재 대면하고 있지 않거나 같은 장소에 있는 다른 플레이어와 이미 대면하고 있는 몬스터를 대면할 수 있습니다.

### 조사
조사자는 현재 장소를 조사하여 단서를 얻으려 시도합니다. 조사자는 장소의 `shroud` 값을 대상으로 `intellect`(<img src="images/skill-intellect.png" width=25>) 테스트를 수행합니다.

스킬 테스트가 성공하면 조사자는 장소에서 단서를 하나 얻습니다. 조사자가 단서를 얻으면 장소 카드에 있는 단서 토큰 하나를 조사자 카드에 놓습니다.

스킬 테스트가 실패하면 단서를 얻을 수 없습니다.

### 회피
조사자는 대면하고 있는 적 하나를 회피시도할 수 있습니다. 조사자는 `agility`(<img src="images/skill-agility.png" width=25>) 스킬을 사용하여 회피하고자 하는 적의 회피 값을 목표로 스킬 테스트를 수행합니다.

스킬 테스트가 성공하면 조사자는 성공적으로 적을 회피합니다. 적은 소진되고, 대면 상태는 깨어집니다. 회피된 적을 조사자의 위협 영역에서 조사자의 현재 장소로 옮겨 더 이상 대면하지 않음을 나타냅니다.

스킬 테스트가 실패하면 회피하지 못하고 대면한 상태로 남게 됩니다.

전략적 팁: 적을 회피하는 것은 매우 중요합니다. 소진된 적들은 조사자에게 자동으로 대면하지 않으며, 기회 공격을 하지 않고, 적 페이즈에서 공격을 하지 않습니다. 비무장 상태이거나 치명적인 적에게서 도망가려면 강력한 공격을 하는 것보다 회피하는 것을 고려해 보십시오.

### 이동
조사자는 이동 액션을 사용하여 연결되어 있는 장소로 이동합니다. 조사자의 미니 카드를 조사자의 현재 장소에서 연결점이 있는 다른 장소로 옮깁니다. 장소의 연결점은 장소 카드의 하단의 아이콘으로 나타나며, 같은 아이콘을 가지고 있는 장소는 연결되어 있습니다.

만일 연결되어 있는 장소가 비공개 상태이면, 조사자가 장소로 이동했을 때, 장소 카드를 뒤집어 공개된 면으로 놓습니다. 공개된 장소에 단서 토큰 놓는 것을 잊지 마십시오.

### 사용
조사자는 자신의 손패 중 에셋이나 이벤트 카드를 선택하여 자원 비용을 지불하고 플레이한다. 카드의 자원 비용과 카드의 타입은 상단 왼쪽 구석에 표시되어 있다.

자원 비용을 지불하기 위해서 조사자는 자신의 자원 풀에서 토큰 풀로 플레이하는 카드의 자원 수와 동일한 개수의 토큰을 이동 시켜야 한다.

각 카드 타입을 플레이하는 규칙은 다음과 같다:
* 이벤트 카드를 플레이하면, 카드의 효과를 적용하고나서 소유자의 버린 카드 더미에 놓는다.
* 에셋 카드를 플레이하면 조사자의 플레이 영역에 놓고 어떤 능력이나 게임 효과에 의해서 플레이를 떠날 때 까지 플레이에 남아 있는다.
* 스킬 카드들은 플레이할 수 없다. 스킬 카드들의 능력과 아이콘을 사용하려면 반드시 플레이어의 손패에서 어떤 스킬 테스트에 사용되어야만 한다.

`fast` 키워드가 있는 카드는 플레이하는 것에 행동을 소모하지 않습니다. 키워드 [fast](rulerefs/Abilities.md#keyword-fast) 참고

### 슬롯
슬롯은 조사자가 플레이에서 동시에 가질 수 있는 특정한 카테고리의 카드 수에 제약을 준다. 자산이 하나 혹은 그 이상의 슬롯 심볼을 가지고 있으면 그 모든 슬롯이 사용가능할 때에만 플레이에 들어올 수 있다.

조사자가 보유한 슬롯은 다음과 같다:
* 동료 슬롯 (<img src="images/slot-ally.png" width=25>) 1
* 신체 슬롯 (<img src="images/slot-body.png" width=25>) 1
* 악세서리 슬롯 (<img src="images/slot-accessory.png" width=25>) 1
* 손 슬롯 (<img src="images/slot-onehanded.png" width=25>) 2
* 아케인 슬롯 (<img src="images/slot-onearcane.png" width=25>) 2

카드에는 다음과 같이 필요한 슬롯이 표기됩니다.
* 동료 슬롯 (<img src="images/slot-ally.png" width=25>)
* 신체 슬롯 (<img src="images/slot-body.png" width=25>)
* 악세서리 슬롯 (<img src="images/slot-accessory.png" width=25>)
* 한손 슬롯 (<img src="images/slot-onehanded.png" width=25>)
* 양손 슬롯 (<img src="images/slot-twohanded.png" width=25>)
* 아케인 슬롯 (<img src="images/slot-onearcane.png" width=25>)
* 양 아케인 슬롯 (<img src="images/slot-twoarcane.png" width=25>)

조사자가 이미 다른 에셋이 사용하고 있는 슬롯을 사용하고자 한다면, 조사자는 새로운 자산이 슬롯을 사용하도록 자신의 조종하에 있는 자산(들)을 버려야 한다.

### 전투
조사자는 자신의 장소에 있는 한 명의 적과 전투를 수행한다. 전투를 수행하는 조사자는 그 적의 `fight` 값을 대상으로 `combat`( <img src="images/skill-combat.png" width=25> ) 스킬 테스트를 수행한다.

테스트가 성공하면, 성공적으로 공격하였고, 조사자는 적에게 1점의 피해를 준다. 어떤 무기들, 주문들 혹은 다른 특별한 공격은 피해의 양을 변경할 수 도 있다. 피해를 준 값과 동일한 양의 피해 토큰을 적 카드위에 올려 놓는다. 적의 체력보다 더 많은 피해 토큰이 올려져 있다면, 그 적은 물리친 것이므로 버린 조우 카드 더미 위에 놓는다. 적 카드의 바닥에 승리 포인트가 적혀있다면 버린 조우 카드 더미에 놓는 대신 승리 카드 더미에 놓는다.

## 적 페이즈
다음의 단계를 수행한다. 플레이에 적이 하나도 없다면 업킵 페이즈를 진행한다.

1. `Hunter` 키워드를 가진 적들을 움직인다. 키워드를 가진 적은 가장 가까운 조사자의 방향으로 연결되어 있는 장소로 한번씩 움직인다. 소진된 `hunter` 적, 그리고 `hunter` 적과 같은 장소에 한명 이상의 조사자가 있다면 움직이지 않는다. `hunter` 적이 한명이상의 조사자가 있는 장소로 움직이면 조사자들 중 한명과 즉시 대면한다. 키워드 [hunter](rulerefs/Abilities.md#keyword-hunter) 참고

2. 적들이 공격한다. 각각의 준비되고 대면한 적들은 대면한 조사자들을 대상으로 공격을 수행한다. 조사자들은 플레이어 순서대로 적들의 공격을 해결한다. 적이 공격할 때에는 피해와 공포를 모두 동시에 대면한 조사자에게 입힌다. 조사자가 받아야 하는 피해와 공포의 양은 적 카드의 텍스트 박스에 나타나 있다.

하나의 적이 공격을 수행하면 공격했다는 표시로 그 적 카드를 소진시킨다(기회 공격을 한 적은 소진되지 않는다).

## 업킵 페이즈
다음의 순서를 진행한다:
1. 각 조사자들은 자신의 미니 카드를 뒤집어(컬러인 면으로) 놓는다.
2. 모든 소진된 카드들을 준비상태로 되돌린다. 조사자와 같은 장소에 있는 준비되어 있으면서 대면되어 있지 않은 적들은 조사자와 대면한다.
3. 각 조사자는 덱에서 카드를 1장 집어 손패에 넣고 자원 1개를 받는다.
4. 손패에 8장이 초과되는 조사자는 카드를 버려서 손패에 8장의 카드만 남게 만든다.

위의 단계를 모두 진행하면, 하나의 라운드가 종료됩니다. 다음 라운드의 미토스 페이즈부터 다시 진행합니다.
