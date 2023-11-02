```mermaid
gantt
    title Design Project
    dateFormat  YYYY-MM-DD

    section main
    Project Assigned         :done,milestone, 2023-10-23,0d
    TA meeting 1             :done,milestone, 2023-10-26,0d
    TA meeting 2             :milestone, 2023-11-09,0d
    TA meeting 3             :milestone, 2023-11-20,0d
    Project due              :milestone, 2023-11-27,0d
    Presenation              :milestone, 2023-11-30,0d
    Demonstration            :milestone, 2023-12-04,0d

    Meeting - Decide on Novel Functionality :done,m1,2023-10-24, 1h


    section Unassigned
    
    Initial protoype : p2, 2023-11-04,1d

    Machine drawing : 2023-11-05, 2023-11-06
    FEA 1            :2023-11-05, 2023-11-06
    Refine Cad model : 2023-11-09, 2023-11-20
    
    Plan for testing    :2023-11-09, 2023-11-20
    Writing             :2023-11-09, 2023-11-20
    Presentation        :2023-11-09, 2023-11-20

    section Noah
    Determine Novel Functionality      :done,2023-10-23, 1d
    Patent Reads                       :active,p1,after m1,2023-11-05
    Cad Hand/Palm                      :active,C2,2023-10-29,2023-11-02
    Send for printing                  :p1,after C2,1d
    section Jordan
    Determine Novel Functionality      :done,2023-10-23, 1d
    Patent Reads                       :active,p2,after m1,2023-11-05
    Floss protoype                      :done,2023-11-01,2h
    section Nate
    Determine Novel Functionality      :done,2023-10-23, 1d
    Patent Reads                       :active,p3,after m1, 2023-11-05
    CAD pulley model                   :done,C1,after m1,2023-10-29
    section Magnus
    Determine Novel Functionality      :done,2023-10-23, 8d
    Patent Reads                       :done,p4,after m1,7d
    section Harry
    Determine Novel Functionality      :done,2023-10-23, 1d
    Patent Reads                            :active,p5,after m1,2023-11-05
    section Andrew
    Determine Novel Functionality           :done,2023-10-23, 1d
    Patent Reads                            :active,p6,after m1,2023-11-05


```
