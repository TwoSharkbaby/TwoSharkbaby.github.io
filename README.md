<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form 연습</title>
    <style>



    </style>
</head>

<body>

    <form action="retrun.jsp">
        <fieldset>
            <legend>반품 정보</legend>
            <p>만일 수령한 상품에 문제가 있다면 즉시 <b>반품 신청</b>해 주세요.</p>
            <p>반품 신청시 상품의 상태를 사진으로 첨부해주세요.</p>
            <hr>
            <input type="file">
        </fieldset>
        <div>
            <input type="submit" value="반품 신청">
            <input type="reset" value="취소하기">
        </div>
    </form>

</body>

</html>
