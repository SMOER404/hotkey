# JavaScript 

## fa - Стрелочная функция 

const $TM_FILENAME_BASE$ = (props) => {
 $END$
};

# React

## rsc - react component 

import React from 'react';

const $TM_FILENAME_BASE$ = () => {
 return (
  <div>
   $END$
  </div>
 );
};

export default $TM_FILENAME_BASE$;

## rscp - react component with proptypes

import React from 'react';
import PropTypes from 'prop-types';

const $TM_FILENAME_BASE$ = props => {
 return (
  <div>
   
  </div>
 );
};

$TM_FILENAME_BASE$.propTypes = {
 $END$
};

export default $TM_FILENAME_BASE$;

## rrdc - react state and dispatch 

import React, { Component } from 'react';
import { connect } from 'react-redux';

function mapStateToProps(state) {

}

function mapDispatchToProps(dispatch) {

}

const $TM_FILENAME_BASE$ = () => {
  return (
   <div>
    $END$
   </div>
  );
}

export default connect(
 mapStateToProps,
 mapDispatchToProps
)($TM_FILENAME_BASE$);

## rrdcp - react state and dispatch with proptypes

import React from 'react';
import { connect } from 'react-redux';

function mapStateToProps(state) {

}

function mapDispatchToProps(dispatch) {

}

const $TM_FILENAME_BASE$ = () => {
  return (
   <div>
    $END$
   </div>
  );
}

$TM_FILENAME_BASE$.propTypes = {

};

export default connect(
 mapStateToProps,
 mapDispatchToProps
)($TM_FILENAME_BASE$);

# Redux

## rdc - reducer

const initialState = [];

export const $TM_FILENAME_BASE$ = (state = initialState, action) => {
  switch (action.type) {

    case `${$END$}`:
      return action.payload;

    default: return state;
  }
};

## saga - saga

export default function* $END$() {
  yield takeLatest(`${BOOK_SUPPLY_LIST_REQUEST}${START}`, $TM_FILENAME_BASE$);
}

function* $TM_FILENAME_BASE$({ payload: data }) {
    try {

    } catch(error) {
       
    }
}

# Hooks

## ue - useEffect 

useEffect(() => {

}, [$END$])

## us - useState 

const [$TM_FILENAME_BASE$, set$TM_FILENAME_BASE$] = useState($END$);

