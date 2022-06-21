### CREATE
#### 테이블 생성
```roomsql
CREATE TABLE <TableName>
(
    <ColumnName1> <DataType> <Constaraint> <Option> Commnet '<Comment>'
  , <ColumnName2> <DataType> <Constaraint> <Option> Commnet '<Comment>'
  , <ColumnName3> <DataType> <Constaraint> <Option> Commnet '<Comment>'
  , ETC...
  , <Constaraint>(<ColumnName>)
)
```

### ALTER
#### 컬럼명 변경
```roomsql
ALTER TABLE <테이블명> CHANGE <기존 컬럼명> <변경할 컬럼명> <데이터 타입>;
```
#### 컬럼 순서 변경
```roomsql
ALTER TABLE <테이블명> MODIFY <컬럼명> <컬럼타입> AFTER <이동할 위치 이전에 있는 컬럼>
```

### DROP

### RENAME

### TRUNCATE