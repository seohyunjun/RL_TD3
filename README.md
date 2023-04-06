# RL_TD3
----

Twin Delayed Deep Deterministic Policy Gradient (A.K.A TD3)

## paper
----
TD3 - [Addressing Function Approximation Error in Actor-Critic Methods(2018.2.26)](https://arxiv.org/abs/1802.09477)

<br>

## Code Environment
----
[OpenAI-gym](https://www.gymlibrary.dev/)
[Mujoco in M1](https://bnmy6581.tistory.com/146)
<br>

<br>

## Mac setting 
```shell
brew install cmake zlib
pip install 'gymnasium[all]'
pip install autorom # 0.42 버전 설치 (0.55 버전 mac m1 subprocess error)
AutoROM --accept-license (rom license Y 후 ale_py rom으로 파일 이동)
# mv /Users/[user_id]/[anaconda/conda/miniforge]/envs/[env_name]/lib/python3.8/site-pakage/AutoRom/rom /Users/[user_id]/[anaconda/conda/miniforge]/envs/[env_name]/lib/python3.8/site-pakage/ale_py/rom/

# require
brew install mpi4py # 
pip install tensorflow-macos # tensorflow-macos (v2 -> compat.v1 )
pip install torch
pip install gymnasium

# fix code 
# gymnasium return 2 parameter
# state, info = env.reset()
# env.step()
```

## Train
----
```bash
## TD3 train
```

 
<br>

## Install Reference 

---- 

<br>

[pip install gym error](https://www.pygame.org/wiki/MacCompile)
<br>

[나만의 GYM 환경 만들기](https://www.youtube.com/watch?v=chVLag1NIAQ)
<br>

[Spinning UP](https://spinningup.openai.com/en/latest/user/installation.html)

<br>


## TD3 Test(Humanoid)
- tianshou benchmark (buffersize 915000, return 5341)
- [tianshou benchmark](https://tianshou.readthedocs.io/en/master/tutorials/benchmark.html#mujoco-benchmark)

<img src="https://github.com/seohyunjun/RL_TD3/blob/main/video/final7.gif" width="75%" height="75%" >

<img src="https://github.com/seohyunjun/RL_TD3/blob/main/ppt/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B32.png" height=80% width=80% >
<img src="https://github.com/seohyunjun/RL_TD3/blob/main/ppt/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B33.png" height=80% width=80% >
