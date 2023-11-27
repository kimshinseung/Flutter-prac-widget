# flutter_widget

A new Flutter project.

## Getting Started

# Stateful Widget
- 상태에 따라 데이터가 변한다.
- 위젯에 데이터를 저장하고 실시간으로 변화를 본다.
- 두가지 상태 존재
- 1. 상태가 없는 위젯
  2. 위젯의 상태로 데이터와 UI가 들어간다.
- 데이터가 변경되면 위젯의 상태도 변화된다.
- **setState함수를 호출해야 변경 사항 적용 가능**

# setState메서드
- 기본적으로 새로운 데이터와 재빌드한다.
- 이 메소드를 사용해야 변경사항이 적용 가능하다.
- 데이터가 수정되었음을 Flutter에게 알리는 역활

# Stateless Widget
 - build 메서드를 통해서 단지 UI 출력한다.
 - 데이터를 가지고 있지 않는다.
