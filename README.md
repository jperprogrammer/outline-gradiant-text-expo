# outline-gradiant-text-expo

## start
expo start

## outline text with linear gradiant border 

```
<Svg style={styles.popular}>
    <linearGradient id="gradiant" x1="0" x2="0" y1="0" y2="80%" gradientUnits="userSpaceOnUse" >
      <stop stopColor="purple" offset="0%"/>
      <stop stopColor="#1e5d7d" offset="100%"/> 
    </linearGradient>
    <text
      fill="none"
      stroke="url(#gradiant)"
      fontSize="30vw"
      fontWeight="bold"
      y="100"
    >
            Popular
    </text>
</Svg>
```

![alt text](https://monosnap.com/file/BLKiBcSbYTnfw7XQIx5IqGfc4g9L27)

