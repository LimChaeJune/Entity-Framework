## Entity Framework Core
### [Entity Framework](https://docs.microsoft.com/en-us/ef/ef6/)란   
      
   보통의 닷넷에서 응용프로그램의 데이터를 데이터베이스에 저장, 검색하기 위해서는  [ADO.NET](https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/ado-net-overview)으로 데이터베이스에 대한 연결을 하고,
   데이터를 조회하거나 수정하기위해 DataSet을 만들고, 데이터를 DataSet에서 .Net의 개체 형식으로 변환하거나 혹은 그 반대로 하여 사용해 비즈니스 로직을 구성했습니다.     
         
   Entity Framework는 이러한 데이터베이스 관련 작업을 자동화하기 위해 .NET 개체를 사용해 데이터베이스로 작업할 수 있게 해주는 Microsoft에서 제공하는 [O/RM(개체 관계형 매퍼)](https://blog.bitsrc.io/what-is-an-orm-and-why-you-should-use-it-b2b6f75f5e2a)
   프레임워크입니다.        
         
   Entity Framework 프레임워크를 이용해 데이테이베이스를 작업하면,
   개발자가 데이터가 저장되는 데이터베이스 테이블에 초점을 맞추고 개발하지 않아도 Class로 구성한 개체를 사용해 데이터로 작업할 수 있습니다.     
   
### EF의 O/RM 기능들
    - 유형에 의존하지 않는 POCO 엔티티 클래스 매핑
    - 데이터 변경 추적
    - ID확인 및 작업 단위
    - LINQ를 통해 데이터베이스 검색을 사용 가능합며, LINQ 쿼리를 특정 데이터베이스 언어로 변환합니다.        
    - LINQ를 이용해 원시 SQL 쿼리를 DB에서 직접 실행할 수 있습니다.


### ASP.NET CORE
    
### WPF
