六号战场战术板的地图资源





```
type MapConfig = {
    type: "r6";
    description: string;
    id: string;
    gadget: {
        name: string;
        type: {
            id: string;
            name: string;
            image: string;
        }[];
    }[];
    maps: {
        name: string;
        floors: {
            name: string;
            maxImageZoomLevel: 0 | 1 | 2 | 3 | 4 | 5;
            maxViewZoomLevel: 1 | 2 | 3 | 4 | 5;
            imageRule: string;
        }[];
    }[];
}
```
