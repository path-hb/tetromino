함수 설명
===============================================

## def main():
    게임의 주요 외형 설정

## def runGame():
    게임의 작동루프 설정

## def makeTextObjs(text, font, color):
    화면에 글자를 쓰고 객체로 반환해주는 함수(사용처 불명)

## def terminate():
    게임 종료 함수

## def checkForKeyPress():
    유저의 키보드 조작을 인지하는 함수

## def showTextScreen(text):
    화면에 문자를 나타내는 함수

## def checkForQuit():
    유저의 게임 종료 조작을 확인하는 함수

## def calculateLevelAndFallFreq(score):
    게임 진행 단계에 따른 블록 낙하 속도 조절 함수

## def getNewPiece():
    새로운 블록을 생성하는 함수

## def addToBoard(board, piece):
    블록을 게임판에 기록하는 함수

## def getBlankBoard():
    빈 게임판을 준비하는 함수

## def isCompleteLine(board, y):
    빈틈없이 채워진 줄을 확인하는 함수

## def removeCompleteLines(board):
    빈틈없이 채워진 줄을 지우는 함수

## def convertToPixelCoords(boxx, boxy):
    로직의 '칸' 정보를 화면상의 '픽셀'위치로 변환하는 함수

## def drawBox(boxx, boxy, color, pixelx=None, pixely=None):
    블록을 구성하는 하나의 사각형을 그리는 함수

## def drawBoard(board):
    화면 중앙에 게임판을 그리는 함수

## def drawStatus(score, level):
    유저의 현재 상태(점수, 단계) 등을 표시하는 함수

## def drawPiece(piece, pixelx=None, pixely=None):
    블록 정보를 바탕으로 화면에 블록을 그리는 함수

## def drawNextPiece(piece):
    다음에 나올 블록을 그리는 함수
