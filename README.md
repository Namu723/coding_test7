# 서울에서 김서방 찾기



def solution(seoul):
    answer = ''
    answer = '김서방은 ' + str(seoul.index('Kim')) +'에 있다'

    return answer

#print(solution(["Jane", "Kim"]))
#ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ



def findKim(seoul):
    return "김서방은 {}에 있다".format(seoul.index('Kim'))
