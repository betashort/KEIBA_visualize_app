### 5.1 Horse

```ts id="2f24eu"
type Horse = {
  id: number;

  mark: string;

  waku: number;

  umaban: number;

  name: string;

  sexAge: string;

  jockey: string;

  odds: number;

  popularity: number;

  pastResults: PastRace[];
};
```

---

# 5.2 PastRace

```ts id="9r85pa"
type PastRace = {
  date: string;

  raceName: string;

  place: string;

  surface: "芝" | "ダ";

  distance: number;

  finish: number;

  time: string;

  agari: string;

  popularity: number;
};
```