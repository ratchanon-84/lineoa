# Examples

|                Telemed Start                |                     More Info                    |                     Announcements                   |                    Schedule                   |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: |
| <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581208/1_f1m5iv.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779581208/2_ys9ozd.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1779250757/%E0%B8%AA%E0%B8%81%E0%B8%A3%E0%B8%B5%E0%B8%99%E0%B8%8A%E0%B9%87%E0%B8%AD%E0%B8%95_2026-05-20_111906_nw7dq3.png" width="200"> | <img src="https://res.cloudinary.com/dpa96jvla/image/upload/v1789440347/C_jbafgv.png" width="200"> |
|    [JSON](./telemedicine-start.json)   |  [JSON](./telemedicine-info.json)  |         [JSON](./announcements.json)        |       [JSON](./general-schedule.json)       |



## Flowchart

```mermaid
flowchart TD
    RM["Tap Rich Menu"]
    RM --> APP["LINE OA / Application"]
    APP --> PROC["Process Request"]
    PROC --> FM["Send Flex Message"]
