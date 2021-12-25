div {
  position: relative;
  background: blueviolet;
  height: 100px;
  overflow: hidden;
}
div:before {
  --a: "продано";
  --b: var(--a) " " var(--a);
  --c: var(--b) " " var(--b);
  --d: var(--c) " " var(--c);
  --e: var(--d) " " var(--d);
  --f: var(--e) " " var(--e);
  --g: var(--f) " " var(--f);
  --h: var(--g) " " var(--g);
  
  content: var(--h);
  color: white;
  display: block;
}
