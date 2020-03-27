https://github.com/eleurent/highway-env/blob/master/scripts/highway_planning.ipynb





## gym render

https://stackoverflow.com/questions/40195740/how-to-run-openai-gym-render-over-a-server

https://github.com/openai/gym/issues/494

```
env = gym.wrappers.Monitor(env, directory, video_callable=lambda episode_id: episode_id%10==0)
```

