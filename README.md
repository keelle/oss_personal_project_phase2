# �����μ��� ����

## ����
�� ������Ʈ�� Python�� `pygame` ���̺귯���� �̿��Ͽ� ������ �����μ��� �����Դϴ�. 
�÷��̾�� �е��� ������ ���� ƨ�� ������ �μ��� ���� ��ǥ�� �մϴ�.

## �ֿ� ���
- Ŭ���� �����μ��� ���� �÷���
- Ű���� �Է��� ���� �е� ����
- ���� ������ �浹 ���� �� ó��
- �پ��� ������ ���

## ���� ����
### ball.py
�� ��ü�� �����ϴ� ���Ϸ�, ���� �Ӽ� �� ������ �����մϴ�.
- `Ball` Ŭ����: ���� �ʱ� ��ġ, �ӵ�, ���� ���� �����ϰ�, �̵� �� �浹 ������ �����մϴ�.

### button.py
���� �� ��ư�� �����ϴ� ���Ϸ�, �پ��� ��ư�� ��ġ �� �ؽ�Ʈ�� �����մϴ�.

### game_state.py
������ ���¸� �����ϴ� ���Ϸ�, ������ �ֿ� ��ҵ��� �ʱ�ȭ�ϰ� ������Ʈ�մϴ�.
- `GameState` Ŭ����: �е�, ��, ����, ������ �� ���� ��Ҹ� �ʱ�ȭ�ϰ�, ������ ����, �Ͻ�����, ���� ���� ���¸� �����մϴ�.

### main.py
������ ���� ������ �����ϴ� ���Ϸ�, ���� ������ �ٽ� ������ ���ԵǾ� �ֽ��ϴ�. ������ �ʱ�ȭ, �̺�Ʈ ó��, ȭ�� ������Ʈ ���� ����մϴ�.

### maps.py
������ �� ���������� ���� ���� ��ġ�� �����ϴ� �����Դϴ�.
- `get_stage_1_bricks()`, `get_stage_2_bricks()`, `get_stage_3_bricks()`, `get_stage_4_bricks()` �Լ�: �� ���������� ���� ��ġ�� �����մϴ�.

### paddle.py
�е� ��ü�� �����ϴ� ���Ϸ�, �е��� �Ӽ� �� ������ �����մϴ�.
- `Paddle` Ŭ����: �е��� �ʱ� ��ġ, ũ��, �ӵ� ���� �����ϰ�, �̵� ������ �����մϴ�.

### setting.py
������ ������ �����ϴ� ���Ϸ�, ȭ�� ũ��, ����, ��Ʈ, �̹��� �ε� ���� �����մϴ�.

## ���� � ü��  (Window �̿ܿ��� �׽�Ʈ�غ��� ���߽��ϴ�. ������ �߻� �� ������� ���� ��Ź�帳�ϴ�.)
| OS      | ���� ���� |
|---------|-----------|
| Windows | :o:       |
| Linux   | :o:       |
| MacOS   | :o:       |


## ��ġ ���
### Windows
1. Python 3.12 ��ġ
2. �ʼ� ���̺귯�� ��ġ
    ```bash
    pip install pygame
    ```

3. ���� ����
    ```bash
    python main.py
    ```

### MacOS
1. Homebrew ��ġ (�̹� ��ġ�Ǿ� �ִٸ� ���� ����):
    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

2. Python ��ġ:
    ```bash
    brew install python
    ```

3. �ʼ� ���̺귯�� ��ġ:
    ```bash
    pip install pygame
    ```

4. ���� ����:
    ```bash
    python main.py
    ```

### Linux
1. Python �� �ʼ� ��Ű�� ��ġ:
    ```bash
    sudo apt update
    sudo apt install python3 python3-pip
    ```

2. pygame ��ġ:
    ```bash
    pip3 install pygame
    ```

3. ���� ����:
    ```bash
    python3 main.py
    ```

## ���� ���� ����
#�߰�����

## �߰� ��� ���� ����
- ���� ��� ��� �߰�
- �е� �̵� �ӵ� ���� ��� �߰�
- ������ �߰� (�� �߰� ������, �� �ӵ� ���� ���� ������ ��)
- ���� ����, ����, �����, �޴� ��ư �߰�
- �¶��� ��ŷ �ý��� �߰�

## ���۷���
- [Pygame ���� ����](https://www.pygame.org/docs/)